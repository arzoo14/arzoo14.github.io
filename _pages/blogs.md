---
title:  "Blogs"
layout: archive
permalink: /blogs/
author_profile: true
comments: true
---

{% for post in site.posts %}
	{% include archive-single.html %}
{% endfor %}


<!-- ### Week 1 to 4

The first week of Google Season of Docs is kick-started with all the joy and enthusiasm. In this phase, I have to focus on transfering and updating the Performance Co-Pilot books - User's and Administrator's Guide (UAG) and Programmer's Guide (PG) from the docbook content into reStructured Text (rst) format such that they can be hosted on the modern community readthedocs.io site. So, what will be the benefit of this? The benefit behind this idea is - It will allow community contributors to more easily change and extend the content. No need of specific set of users to maintain the content website.  

I started the work with the basic setup of the sphinx configuration for the Performance Co-Pilot (PCP) documentation. The PCp books - User's and Administ -->