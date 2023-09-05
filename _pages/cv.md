---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Carnegie Mellon University**
  * B.S. in Computer Science with University Honors, Minor in Mathematical Science, 2018-2022
  * M.S. in Computer Science (Thesis Based), 2022-2023

Teaching
======
* Teaching Assistant for 15-213/513 Introduction to Computer Systems, Summer 2023
* Teaching Assistant for 10-701 Introduction to Machine Learning (Ph.D.), Fall 2023
* Teaching Assistant for 15-712 Advanced Operating Systems and Distributed Systems, Fall 2023

Work experience
======
*  **Multicomp Research Internship**
    * **Duration:** May - AUG. 2020 
    * **Employer:** School of Computer Science, CMU
    * **Supervisor:** Dr. Louis-Philippe Morency, Language Technologies Institute, CMU
    * **Duties include:**
      * develop hierarchical autoencoder networks for complex multimodal data feature extractions, including Video, Audio, and Text modality;
      * prove effectiveness of the network on downstream classification tasks from CMU-MOSEI, MOSI, and IEMOCAP datasets

* **Research Assistant**
    * **Duration:** JUL. 2021 - AUG. 2023
    * **Employer:** Mohimani Lab, School of Computer Science, CMU
    * **Supervisor:** Dr. Hosein Mohimani, Computational Biology Department, CMU
    * **Duties include:**
      * Design and implement efficient algorithms for nonribosomal peptide discovery through GNPS dataset, a public mass-spectrometry database that currently contains over 717 million mass-spectrometry data
      * Design and Implement Machine Learning methods for predicting bindings between protein sequences and peptides for small molecule discoveries.


Skills
======
* **Programming Languages**: C/C++, Python, Golang, SML, Rust(Novice)
* **Libraries**: PyTorch, Python Libraries, C++ STL, MySQL(Novice)
* **Tools**: Latex, Unix Shell, Anaconda, Microsoft Office
* **Experiences**: Algorithm Design, Machine Learning, Distributed Systems, Statistical Modeling, Biostatistical Analysis


Selected Projects
======
* **Efficient clustering and spectral library search under large data scale**
  * **Duration:** AUG. 2021 - JUL. 2023
  * **Support:** awards from [NSF 2117640](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2117640&HistoricalAwards=false), U.S. Department of Energy [DE-SC0021340](https://pamspublic.science.energy.gov/WebPAMSExternal/Interface/Common/ViewPublicAbstract.aspx?rv=a601ce84-b365-4772-87d3-9ee13d943635&rtc=24&PRoleId=10)
  * **Supervisor:** Dr. Hosein Mohimani, Computational Biology Department, CMU
  * **Keywords:** C++, Rust, Algorithms, Data mining, Software Engineering, Biostatistics
  * One of the main contributors for designing and implementing MASST+ & Networking+, two toolkits for large-scale spectral library clustering, searching and analysis that’s three orders of magnitudes faster than the state of art
  * Our contribution greatly improves the efficiency of natural product discoveries and genome mining
  * [Paper](http://YudongL2000.github.io/files/MASST+.pdf) accepted by Nature Biotechnology
  * [Github](https://github.com/mohimanilab/MASSTplus)
  
* **Learning A-domain substrate specificities using AdenPredictor**
  * **Duration:** DEC. 2021 - OCT. 2022
  * **Support:** [NSF award 2117640](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2117640&HistoricalAwards=false)
  * **Supervisor:** Dr. Hosein Mohimani, Computational Biology Department, CMU
  * **Keywords:** Python, Machine Learning, Bioinformatics
  * Participated in developing AdenPredictor, a powerful toolkit for identifying bioactive compounds for drug discoveries.
  * Our tool predicts the binding of amino acids to A-domain protein subsequences using ensembled ML Models that incorporates 3-dimensional domain structures from AlphaFold2, achieving about 90% accuracy on testing data
  * [Paper](http://YudongL2000.github.io/files/adenPredictor.pdf) published on Bioinformatics
  * [Github](https://github.com/MihirMongia/AdenPredictor)
  
* **High-Modality Multimodal Transformer**
  * **Duration:** JUN. 2022 - FEB. 2023
  * **Support:** Meta, [NSF award 1750439](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1750439&HistoricalAwards=false), [NSF award 1722822](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1722822&HistoricalAwards=false)
  * **Supervisor:** Dr. Louis-Philippe Morency, Language Technologies Institute, CMU
  * **Keywords:** Python, PyTorch, Deep Learning
  * Participated in the development of HighMMT, a model capable of handling over 8 modalities including spoken language, video, gestures, text and robot sensory data through few-shot modality transfer
  * Improved the tradeoff between performance and parameter-efficiency over existing state-of-art models
  * [Paper](http://YudongL2000.github.io/files/highMMT.pdf) published on TMLR
  * [Github](https://github.com/pliang279/HighMMT)
  
* **DynPartition**
  * **Duration:** FEB. - MAY 2022
  * **Supervisor:** Prof. Philip Gibbons, Computer Science Department, CMU
  * **Keywords:** Python, Distributed Machine Learning, Distributed Systems
  * Proposed and implemented a novel rein-forcement learning-based scheduler that performs dynamic partitioning of computation workload across multiple heterogeneous GPUs for large neural network inference tasks
  * explored an important area of research in distributed machine learning under Cloud Cluster settings
  * [Report](http://YudongL2000.github.io/files/RL_scheduler.pdf)
  * [Github](https://github.com/YudongL2000/DynPartition)

* **Distributed Bitcoin Miner**
  * **Duration:** AUG. - OCT. 2020
  * **Supervisor:** Dr. Heather Miller, Computer Science Department, CMU
  * **Keywords:** Golang, Distributed Systems, Networking
  * Designed a mock distributed bitcoin miner based on Remote Procedural Calls (RPC) between client-server interactions
  * The miner runs on LSP (Live Sequence Protocol) capable of handling computational intensive tasks and recovering from sudden failures
  * [Github](https://github.com/YudongL2000/Distributed_Bitcoin_miner)


* **ECLM: Expansion Language Models for Conditional Adaptation**
  * **Duration:** JUL. 2023 - Present
  * **Supervisor:** Dr. Louis-Philippe Morency, Language Technologies Institute, CMU
  * **Keywords:** Python, PyTorch, Deep Learning, Natural Language Processing
  * Constructing a pipeline for Multimodal video captioning and QA task with easy few-shot adaptation to large Large Language Models from small pretrained language models
  * Aim to incorporate modalities from visual, audio, medical and graph datasets into the pipeline to create a highly-capable multimodal QA system

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  

