---
layout: photolist
title: Practicals
menu: true
---
*Spring 2025*


# Practicals


{% assign practicals = (site.data.2021.assignments | where: "selected", "y") %}
{% for practical in practicals %}
{% include assignment.html lecture=practical %}
{% endfor %}

