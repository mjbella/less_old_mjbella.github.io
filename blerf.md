---
layout: page
title: Project Page
---
{% for proj in site.Projects %}
    <div class="proj">
        <h2><a href="{{ proj.url }}">{{ proj.title }}</a></h2>
    </div>
{% endfor %}
