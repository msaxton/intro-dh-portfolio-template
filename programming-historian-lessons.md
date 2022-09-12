---
layout: page
title: Lessons
permalink: /programming-historian-lessons/
---

<ul>
  {% for lesson in site.lessons %}
    <li>
      <h2><a href="{{ lesson.url | prepend: site.baseurl}}">{{ lesson.title }}</a></h2>
      <p>{{ lesson.description }}<p>
    </li>
  {% endfor %}
</ul>