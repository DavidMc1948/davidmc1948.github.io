---
layout: default
title: PDF List
---

# PDF Files

The file name has to be meaningful for this to be useful.   

#{% assign image_files = site.static_files | where: "image", true %}
#{% for myimage in image_files %}
#  {{ myimage.path }}
#{% endfor %}

{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
<a href="{{ myimage.path }}">{{myimage.path}}</a>
{% endfor %}
