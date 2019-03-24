---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

#layout: home
layout: default
title: Home
permalink: /
---

This site provides free English Tutorials.

<!-- <h2>{{ site.data.topics.topics_title }}</h2> -->
<ol>
   {% for item in site.data.topics.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
      <br/>
   {% endfor %}
</ol>

<!-- 
1. [About]({{site.baseurl}}/about/)
2. [Contact]({{site.baseurl}}/contact/)
3. [My Pet]({{site.baseurl}}/essays/my_pet/)
-->
