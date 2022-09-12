---
layout: page
title: Project Evaluations
permalink: /dh-project-evaluations/
---

<ul>
  {% for evaluation in site.evaluation %}
    <li>
      <h2><a href="{{ evaluation.url }}">{{ evaluation.title }}</a></h2>
      <p>{{ evaluation.description }}<p>
    </li>
  {% endfor %}
</ul>
