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

Niche construction is a component of contemporary evolutionary theory (i.e., the "extended evolutionary synthesis") that emphasizes the feedback between behavioral alterations of an organism's environment, and the selective environments into which offspring are borne.  This feedback loop creates a form of "ecological inheritance" and thus constitutes a way in which fitness is affected within populations.  The environment-altering aspects of human behavior are clear and have been studied by anthropologists, ecologists, and society at large for decades:  our "extended phenotype" and the "trace fossils" we leave behind on the landscape could not be clearer:  their influence now extends to earth's climate system, and some of our constructions and artifacts can be seen from Earth orbit.  

The second half of the feedback loop has been studied in qualitative terms, is poorly understood in quantitative terms when integrated into formal models of cultural transmission.  In this half of the loop, individuals are born and socialized in culturally modified environments, stocked with tools, objects, and modifications created earlier.  And thus their learning is guided and constrained by the cultural environment itself, leading to bodies of knowledge and skills specific to that group and surroundings.  

The temporal and inter-generational maintenance of the learning environment has been described by Odling-Smee, Laland, Jablonka and Lamb, and philosophers of biology Kim Sterelny (esp. in his most recent book _The Evolved Apprentice_) and William Wimsatt.  In its earliest and fragmentary forms, this looks more like artifact- and place-assisted social learning of specific tasks, while in more elaborated forms (e.g., shop class in contemporary schools) a variety of social institutions, infrastructure, artifacts, and forms of instruction are passed down and combined to "scaffold" the learning of complex skills and information.  

Description of this kind of structure to social learning has been descriptive for the most part.  Constructing quantitative models of cultural transmission with this sort of structure is a daunting challenge, but absolutely necessary if we want formal models which can be fitted to realistic data for explanatory or predictive purposes.  

This project aims to construct a simplified and abstracted formal model of transmission in which [structured information](/projects/structuredinfo) is combined with a pool of simulated artifacts and agents from which individuals learn.  The normal Boyd and Richerson modes of transmission and social learning still apply, but individuals might only learn certain information in the correct context -- i.e., when surrounded by appropriate artifacts and other individuals with appropriate information.  This kind of model is clearly only a starting point, but understanding how such models alter the dynamics of our existing CT models is a stepping stone to situation-specific, richer models which incorporate richer contexts, via less abstraction.

In particular, I am exploring generic ways of adding such features to simulation models of cultural transmission processes, in a way that facilitate building richer models but preserving comparability between simple and richer models so that we can understand what effects arise out of the increased detail and mechanism.  

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



















