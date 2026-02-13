---
layout: page
title: Projects
permalink: /projects/
---

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
**{{ project.timeline }}**  
{{ project.description }}

{% endfor %}
