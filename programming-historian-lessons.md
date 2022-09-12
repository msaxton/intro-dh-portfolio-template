---
layout: page
title: Lessons
permalink: /programming-historian-lessons/
---
<div>
  {% for lesson in site.lessons %}
  <div>
      <h2><a href="{{ lesson.url | prepend: site.baseurl}}">{{ lesson.title }}</a></h2>
      <p>{{ lesson.description }}<p>
  {% endfor %}