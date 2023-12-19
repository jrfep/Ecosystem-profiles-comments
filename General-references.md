---
layout: default
title: General references
---

# All references

{% for item in site.data.references %}
* {{ item[1] }}
{% endfor %}
