---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Carnegie Mellon University
  * B.S. in Computer Science with University Honors, Minor in Mathematical Science, 2018-2022
  * M.S. in Computer Science (Thesis Based), 2022-2023

Work experience
======
* Summer 2020: Multicomp Research Internship
  * Multicomp Lab, Language Technologies Institute, CMU
  * Supervisor: Dr. Louis-Philippe Morency
  * Duties include:
    * develop hierarchical autoencoder networks for complex multimodal data feature extractions, including Video, Audio, and Text modality;
    * prove effectiveness of the network on downstream classification tasks from CMU-MOSEI, MOSI, and IEMOCAP datasets


* JUL. 2021 - AUG. 2023: Research Assistant
  * Mohimani Lab, School of Computer Science, CMU
  * Supervisor: Dr. Hosein Mohimani
  * Duties include:
    * Designed and implemented efficient algorithms for nonribosomal peptide discovery through GNPS dataset, a public mass-spectrometry database that currently contains over 717 million mass-spectrometry data
    * Designed and Implemented ML methods for predicting bindings between protein sequences and peptides for small molecule discoveries.
  
Skills
======
* Efficient-Algorithm Design
* Machine Learning
  * Multimodal Machine Learning
  * Natural Language Processing
  * Statistical Machine Learning
* Distributed Systems
* Statistical Modeling
* Biostatistical Analysis

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

