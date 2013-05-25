---
layout: post
title: Online Lab Notebook
---
For several years, I've used an Instiki wiki for a lab notebook, running locally on my laptop (and sync'd and backed up with Dropbox).  Local Instiki had the advantage of being simple, and strongly supporting both MathML and LaTeX output.  The downside was that I couldn't easily have both offline editing, and a publicly accessible "open" lab notebook.  

So I also tried an experiment with Wikispaces, and migrated some of my old content to a new wiki, and started writing new notebook pages there.  The math support was OK, which is fine because I don't really have a ton of mathematical content yet, the code snippet support OK, but in general it's designed to be user-friendly, not developer-as-user-friendly.  And, being a hosted service, there's no offline service.  So I found that I'd write something in a text file on a plane, for example, and then cut and paste it into Wikispaces when I got home.  

This is the third iteration of an open lab notebook/wiki/research blog.  I'm using GitHub as the means to tie everything together, along with the superb Jekyll templating/website construction engine built by the GitHub folks.  The idea here is that everything is written locally and saved in the Git repository, but when I push it to GitHub, the site is automatically built and updated.  A static version of the site is thus available online for public browsing, while I can edit from anywhere.  

I've got a long way to go with templates, layouts, and some decisions about static pushes and local builds, versus letting GitHub built it all.  The sticking point here is the Jekyll-Scholar plugin, which automatically builds bibliographies and handles references.  Plugins don't work with GitHub Pages given the <code>--safe</code> flag that everything is built with.  So I might have to do some fiddling or reconstruction for a bit. 

Once it's all working with some new and dummy posts, I'll port content and make this my default research notebook.  