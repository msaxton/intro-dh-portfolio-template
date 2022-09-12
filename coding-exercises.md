---
layout: page
title: Coding Exercises
permalink: /coding-exercises/
---

<ul>
  {% for exercise in site.exercises %}
    <li>
      <h2><a href="{{ exercise.url | prepend: site.baseurl }}">{{ exercise.title }}</a></h2>
      <p>{{ exercise.description }}<p>
    </li>
  {% endfor %}
</ul>