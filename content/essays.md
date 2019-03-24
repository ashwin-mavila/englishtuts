---
layout: level1
title: Essays
permalink: /content/essays/
---

<h3>Essays</h3>

<ol>
   {% for item in site.data.essays.docs %}
      <li><a href="{{ item.url | absolute_url}}">{{ item.title }}</a></li>
      <br/>
   {% endfor %}
</ol>
