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
* Programming Languages:
  * C/C++
  * Python
  * Golang
  * SML
  * Rust(Novice)
* Libraries:
  * PyTorch
  * Python Libraries
  * C++ STL
  * MySQL(Novice)
* Tools
  * Latex
  * Unix Shell
  * Anaconda
  * Microsoft Office
* Experienced in
  * Algorithm Design
  * Machine Learning
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
Major Projects

* Efficient clustering and spectral library search under large data scale
  * AUG. 2021 - JUL. 2023
  * Supported by: awards from NSF 2117640, U.S. Department of Energy DE-SC0021340
  * Supervisor: Dr. Hosein Mohimani
  * Keywords: C++, Rust, Algorithms, Data mining, Software Engineering, Biostatistics
  * Details:
    * One of the main contributors for designing and implementing MASST+ & Networking+, two toolkits for large-scale spectral library clustering, searching and analysis that’s three orders of magnitudes faster than the state of art
    * Our contribution greatly improves the efficiency of natural product discoveries and genome mining
    * Paper accepted by Nature Biotechnology as co-first author


* Learning A-domain substrate specificities using AdenPredictor
  * DEC. 2021 - OCT. 2022
  * Supported by: NSF award 2117640
  * Supervisor: Dr. Hosein Mohimani
  * Keywords: Python, Machine Learning, Bioinformatics
  * Details:
    * Participated in developing AdenPredictor, a powerful toolkit for identifying bioactive compounds for drug discoveries.
    * Our tool predicts the binding of amino acids to A-domain protein subsequences using ensembled ML Models that incorporates 3-dimensional domain structures from AlphaFold2, achieving about 90% accuracy on testing data
  

* High-Modality Multimodal Transformer
  * JUN. 2022 - FEB. 2023
  * Supported by: Meta, NSF award 1750439 and 1722822
  * Supervisor: Dr. Louis-Philippe Morency
  * Keywords: Python, PyTorch, Deep Learning
  * Details:
    * Participated in the development of HighMMT, a model capable of handling over 8 modalities including spoken language, video, gestures, text and robot sensory data through few-shot modality transfer
    * Improved the tradeoff between performance and parameter-efficiency over existing state-of-art models
  


* DynPartition
  * FEB. - MAY 2022
  * Computer Science Department, CMU
  * Supervisor: Prof. Philip Gibbons
  * Keywords: Python, Distributed Machine Learning, Distributed Systems
  * Details:
    * Proposed and implemented a novel rein-forcement learning-based scheduler that performs dynamic partitioning of computation workload across multiple heterogeneous GPUs for large neural network inference tasks
    * explored an important area of research in distributed machine learning under Cloud Cluster settings



* Distributed Bitcoin Miner
  * AUG. - OCT. 2020
  * Computer Science Department, CMU
  * Supervisor: Dr. Heather Miller
  * Keywords: Golang, Distributed Systems, Networking
  * Details:
    * Designed a mock distributed bitcoin miner based on Remote Procedural Calls (RPC) between client-server interactions
    * The miner runs on LSP (Live Sequence Protocol) capable of handling computational intensive tasks and recovering from sudden failures



* ECLM: Expansion Language Models for Conditional Adaptation  
  * JUL. 2023 - Present
  * Multicomp Lab, Language Technologies Institute, CMU
  * Supervisor: Dr. Louis-Philippe Morency
  * Keywords: Python, PyTorch, Deep Learning, Natural Language Processing
  * Details:
    * Constructing a pipeline for Multimodal video captioning and QA task with easy few-shot adaptation to large Large Language Models from small pretrained language models
    * Aim to incorporate modalities from visual, audio, medical and graph datasets into the pipeline to create a highly-capable multimodal QA system




Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

