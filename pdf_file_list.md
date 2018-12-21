---
layout: default
title: PDF List
---

# PDF Files

I still have to figure out how to do proper links  

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
