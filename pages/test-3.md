---
title: Test1
tags: [formatting]
keyords: notes, tips, cautions, admonitions
last_updated: March 27, 2018
layout: default
summary: "This page describes the content"
permalink: test-3.html
---
# {{page.title}}
This is Test-3 page.

<ul>
<li>my item </li>
{% for item in site.data.toc.groups %}
  <li> {{ item.title }} </li>
{% endfor %}  

</ul>
