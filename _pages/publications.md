---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<style>
    .button-container {
      display: flex;         /* Enables flexbox */
      justify-content: center; /* Centers buttons horizontally */
      align-items: center;     /* Aligns them vertically */
      gap: 15px;               /* Adds equal space between buttons */
      width: 100%;             /* Ensures it spans the full width */
      margin: 20px 0;          /* Adds space above and below the line */
    }
    .box_link {
      display: inline-flex; /* Changed from inline-block to align items easily */
      align-items: center;  /* Centers icon and text vertically */
      gap: 10px;            /* Adds space between the icon and the text */
      padding: 0 20px;
      background-color: #a4dced; /* Dark GitHub-style color */
      color: #444444;
      text-decoration: none;
      border-radius: 6px;
      font-weight: 600;
      height: 50px;
      box-sizing: border-box;
      border: none;
    }

    .box_link img {
      height: 24px;      /* Matches the text size visually */
      width: auto;       /* Maintains original proportions */
      display: block;    /* Removes extra bottom spacing */
    }

    .box_link:hover {
      background-color: #bdf0ff;
    }
</style>
<div class="button-container">
    {% if site.author.googlescholar %}
      <a target="_blank" rel="noopener noreferrer" href="{{site.author.googlescholar}}" class="box_link">
        Google Scholar
        <img src="{{ "/images/logo_scholar.png" | prepend: base_path }}">  
      </a>
    {% endif %}
    {% if site.author.researchgate %}
      <a target="_blank" rel="noopener noreferrer" href="{{site.author.researchgate}}" class="box_link">
        ResearchGate
        <img src="{{ "/images/logo_rg.png" | prepend: base_path }}">  
      </a>
    {% endif %}
</div>

{% include base_path %}
<!-- New style rendering if publication categories are defined -->
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
