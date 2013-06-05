---
layout: default
title: Cultural Transmission of Structured Information
tags: [cultural transmission, state space, structured information, evodevo, development, thick models]
date: 2013-05-28 00:00:00
---

## {{ page.title }} ##



<div id="home">
<h3>Project Description</h3>
</div>

Theoretical, experiment, and ethnographic studies of cultural transmission have long recognized that the information acquired by social learning is not atomistic nor holistic, but structured (Mesoudi and O'Brien 2008 employ the term "hierarchical").  

By "structure," I simply mean that cultural information often (if not almost always) comes in pieces which have relationships to other pieces.  An example of such relationships is "abstract vs concrete," while another is that Piece A is a "prerequisite" to Piece B.  Many other such relationships exist, of course, because concepts and sets of concepts bear many _semantic_ relationships.  

Despite the recognition in theory and observation that cultural information, skills, and traits are structured in this way, our formal models (both mathematical and simulation) tend to represent cultural variation as _unstructured._  This is a result of employing the mathematical machinery of population genetics, for the most part.  We treat cultural traits as if they were genetic loci, with variants as alleles.  The copying and innovation rules we implement -- again, for the most part -- operate on single loci.  Occasionally we model interactions between loci, as when one locus models the level of conformist bias an individual displays, which affects the copying of another locus containing a substantive design variant.  

The literature on the _evolution of cumulative culture and transmission itself_ is also somewhat reflective on the nature of the cultural information load itself (aside:  we have no good term which mimics "genotype" or "genome" and I refuse to use "memeome" or anything reminiscent of memetics).  Joe Henrich, among others, have modeled the consequences of different transmission rules and demographic models, on the accumulation of cultural information, with very interesting results. 

But none of this work really treats cultural variation as _structured_, in the sense described here.  The closest approach is Mesoudi and O'Brien's (2008) modeling of cultural "recipes" (sensu Neff 1992, Krause 1985) and their importance compared to "holistic" or "atomistic" (their term is "diffusionist") structures.  

This project follows in Mesoudi and O'Brien's footsteps, but seeks to extend the notion of a "recipe" to encompass a variety of semantic relationships.  Some blocks of cultural information do, in fact, comprise something like a "recipe," _sensu stricto_.  But we also need to understand what the spatiotemporal and time series consequences are for the transmission of information that has prerequisite-type relationships, since these are ubiquitious in complex technologies and tasks.  

In particular, "prerequisite" information and "abstract/concrete" relationships should create emergent effects that William Wimsatt has called "generative entrenchment," a key aspect of both genetic and cultural "evo-devo" systems.  To date, it has been impossible to see such effects in our simple "beanbag" cultural transmission models.  

Little of this project will be composed of analytical models.  The ability to represent semantic relationships like those described is algorithmic and data-driven.  Thus, the primary tool is simulation modeling, employing semantic technology derived from a decade of work in cognitive science, computer science, and the Semantic Web.  

This project is just getting off the ground, but I am laying the groundwork for code modules which will allow simple versions of structure information models.  

<div id="home">
<h3>Project Notes</h3>
</div>

<ul class="posts">
{% for post in site.categories["structured information project"] %}
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



















