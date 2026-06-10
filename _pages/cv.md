---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<div class="{{ include.type | default: "list" }}__item">
  <article class="archive__item" itemscope itemtype="http://schema.org/CreativeWork">
  <div class="button-container">
      <a target="_blank" rel="noopener noreferrer" href="https://ludovicdematteis.github.io/files/CV_DeMatteis.pdf" class="box_link">
	Download PDF
	<img src="{{ "/images/file_icon.png" | prepend: base_path }}">  
      </a>
  </div>
  </article>
</div>

Education
======

{% include archive-single-cv-education.html %}

Publications
======
{% assign sorted_publications = site.publications | sort: 'year' | reverse %}
{% assign current_year = nil %}
{% for post in sorted_publications %}
  {% if post.year != current_year %}
    {% if current_year %}
</ul>
    {% endif %}
<h2 style="margin-top:1em; margin-bottom:-1em;">{{ post.year }}</h2>
<ul>
    {% assign current_year = post.year %}
  {% endif %}
  {% include archive-single-cv.html %}
  {% if forloop.last %}
</ul>
  {% endif %}
{% endfor %}

Teaching
======
{% assign sorted_teaching = site.teaching | sort: 'date' | reverse %}
{% assign current_year = nil %}
{% for post in sorted_teaching %}
  {% assign item_year = post.date | date: "%Y" %}
  {% if item_year != current_year %}
    {% if current_year %}
</ul>
    {% endif %}
<h2 style="margin-top:1em; margin-bottom:-1em;">{{ item_year }}</h2>
<ul>
    {% assign current_year = item_year %}
  {% endif %}
  {% include archive-single-cv.html %}
  {% if forloop.last %}
</ul>
  {% endif %}
{% endfor %}
