---
layout: photolist
title: Syllabus
menu: yes
---

*Spring 2024*


# Lectures

{% assign lectures = (site.data.2021.lectures | where: "selected", "y") %}
{% for lecture in lectures %}
{% include lecture.html lecture=lecture %}
{% endfor %}


