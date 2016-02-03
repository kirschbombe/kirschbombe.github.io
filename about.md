---
layout: page
title: About
---

I am the Librarian for Digital Collections and Scholarship at [UCLA's Digital Library Program](http://digital2.library.ucla.edu) interested in digital libraries; digital and analog approaches to bibliography, book history, and archival studies; digital scholarly editing; and translation. I also regularly consult and collaborate with faculty and students on projects related to digital scholarship and pedagogy. My background is in German literature, philosophy, book history, and textual studies. When I'm not occupied with the above or tinkering with things digital, I enjoy printmaking and translating German poetry.

{% if site.data.travel.size > 0 %}
***

## Upcoming Conferences, Workshops, & Presentations

{% include travel.html %}

{% endif %}
***

## Recent Posts
<ul>
  {% for post in site.posts limit: 5 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
