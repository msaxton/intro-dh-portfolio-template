---
layout: default
title: Lessons
permalink: /programming-historian-lessons/
---
# Programming Historian Lessons
## [SAMPLE: Introduction to stylometry with Python]({{ site.baseurl }}{% link lessons-stylometry.md %})
This lesson uses Python packages to discover the authors fo the federalist papers.

<h1>Programming Historian Lessons</h1>

<ul>
  {% for lesson in site.lessons %}
    <li>
      <h2><a href="{{ lesson.url }}">{{ lesson.title }}</a></h2>
      <p>{{ lesson.description }}<p>
    </li>
  {% endfor %}
</ul>