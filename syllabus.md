---
layout: photolist
title: Syllabus
menu: yes
---

*Spring 2025*


# Lectures

{% assign lectures = (site.data.2025.lectures | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


