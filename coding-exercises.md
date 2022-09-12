---
layout: page
title: Coding Exercises
permalink: /coding-exercises/
---

<div>
  {% for exercise in site.exercises %}
    <div>
      <h2><a href="{{ exercise.url | prepend: site.baseurl }}">{{ exercise.title }}</a></h2>
      <p>{{ exercise.description }}<p>
  {% endfor %}
<!---Note: Liquid syntax seems to close open tags without adding them--->