---
layout: default
title: Coarse Grained Models of Cultural Transmission
tags: [cultural transmission, coarse graining, renormalization, time averaging]
date: 2013-05-28 00:00:00
---

## {{ page.title }} ##



<div id="home">
<h3>Project Description</h3>
</div>

CONTENT

<div id="home">
<h3>Project Notes</h3>
</div>

<ul class="posts">
{% for post in site.categories["coarse grained model project"] %}
         <li><a href="{{ post.url }}">{{ post.title }}</a>  <span class="index_publish_date">{{ post.date | date_to_string }}</span></li>
{% endfor %}
</ul>





Tagged
------
<div class="taglist">
{{ page.tags | array_to_sentence_string }}
</div>


<div class="project_publish_date">
{{ page.date | date_to_string }}
</div>



















