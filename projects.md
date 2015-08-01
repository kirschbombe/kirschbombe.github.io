---
layout: page
title: Projects
---

The projects below include digital humanities and dh pedagogy projects, papers and conference talks, as well as tutorials and workshop materials.

<!-- Automatic project list generator -->

{% for project in site.data.projects.dh %}
<div class="toc">
<img src="{{ project.avatar }}" class="avatar" />
<a href="{{ project.url }}">{{ project.title }}</a>
<p>{{ project.snippet }}</p>
</div>
{% endfor %}

<!--# Select Research
{% for project in site.data.projects.other %}
<div class="toc">
<img src="{{ project.avatar }}" class="avatar" />
<a href="{{ project.url }}">{{ project.title }}</a>
<p>{{ project.snippet }}</p>
</div>
{% endfor %}-->
