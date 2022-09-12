---
layout: page
title: Project Evaluations
permalink: /dh-project-evaluations/
---

<div>
  {% for evaluation in site.evaluations %}
    <div>
      <h2><a href="{{ evaluation.url | prepend: site.baseurl }}">{{ evaluation.title }}</a></h2>
      <p>{{ evaluation.description }}<p>
  {% endfor %}
<!---Note: Liquid syntax seems to close open tags without adding them--->
