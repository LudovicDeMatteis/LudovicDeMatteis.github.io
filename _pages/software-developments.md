---
layout: archive
permalink: /software-development/
title: "Software Developments"
author_profile: true
---

<div class="wordwrap">
You can find here a (non-exhaustive) list of my software contributions. 
Feel free to contact me for any of those and find more of my work on <a href="{{site.author.github}}">my GitHub</a>.
</div>

{% for post in site.softwares reversed %}
    {% include archive-single.html %}
{% endfor %}
