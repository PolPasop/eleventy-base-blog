---
layout: layouts/home.njk
eleventyNavigation:
  key: nav.projects
  order: 1
---

<h1>Projects</h1>

{% set projectslist = collections.projects %}
{% include "projectslist.njk" %}