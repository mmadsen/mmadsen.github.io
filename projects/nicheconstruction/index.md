---
layout: default
title: Niche Construction and Embodied Cultural Transmission
tags: [cultural transmission, niche construction, artifact pools]
date: 2013-05-28 00:00:00
---

## {{ page.title }} ##



<div id="home">
<h3>Project Description</h3>
</div>








<div id="home">
<h3>Project Notes</h3>
</div>

<ul class="posts">
{% for post in site.categories["niche construction project"] %}
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



















