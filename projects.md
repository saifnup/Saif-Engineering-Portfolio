---
layout: default
title: Projects
permalink: /projects/
---

<h2>Projects</h2>

<ul>
{% for project in site.projects %}
  <li>
    <a href="{{ project.url }}">{{ project.title }}</a><br>
    <em>{{ project.timeline }}</em><br>
    {{ project.description }}
  </li>
  <br>
{% endfor %}
</ul>
