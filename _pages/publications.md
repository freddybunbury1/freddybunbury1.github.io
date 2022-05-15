---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


I am a Postdoctoral fellow working in Arthur Grossman and Devaki Bhaya's lab at the Carnegie Institution for Science Department of Plant Biology on the Stanford Campus. I currently study the phenotypes and genetics of thermophilic bacteria from Yellowstone hot spring biofilms to better understand how these biofilm communities have coevolved to thrive in such extreme environments. In my PhD at Cambridge University, I studied the metabolic consequences of vitamin B12 deprivation in microalgae, and their mutualistic relationships with B12-producing bacteria.

During the COVID-19 lockdown in 2020, I worked with statisticians and medical doctors from the University of Chicago, University of California Santa Barbara, and Imperial College London on two COVID-related projects. The first project sought to improve the accuracy of COVID diagnoses by combining lateral flow assays with questionnaire results ([enriching antigen testing]()). The second devised a framework and user-friendly tool to estimate COVID transmission risk at live events ([management of live events]()).


  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=_Tn0l5UAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
