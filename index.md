---
show-avatar: false
layout: page
---

{% assign about= site.pages | where: 'name','aboutme.md' %}
{{about}}

## Articles

{% assign publications = site.pages | where: 'name','publications.markdown' %}
{{publications}}