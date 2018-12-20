---
layout: default
title: PDF List
---

# PDF Files

A list of PDF files will appear here. At this stage I only know how to add the links manually.  

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
