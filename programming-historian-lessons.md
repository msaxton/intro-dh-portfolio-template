---
layout: default
title: Lessons
permalink: /programming-historian-lessons/
---
<h1>Programming Historian Lessons</h1>

<ul>
  {% for lesson in site.lessons %}
    <li>
      <h2><a href="{{ lesson.url }}">{{ lesson.title }}</a></h2>
      <p>{{ lesson.description }}<p>
    </li>
  {% endfor %}
</ul>