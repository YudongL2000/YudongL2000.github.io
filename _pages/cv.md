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
  * **B.S. in Computer Science** , 2018-2022
    * Minor in Mathematical Science
    * **University Honors**
    * **CGPA:** 3.76/4.00
  * **M.S. in Computer Science (Thesis Based)**, 2022-2023
    * **CGPA:** 4.02/4.30
  * **Selected Advanced Courses:**
    * **Algorithms & Complexity:** Algorithms for Big Data (15-859), Algorithm Design and Analysis (15-451)
    * **Systems:** Advanced Operating Systems and Distributed Systems (15-712), Distributed Systems (15-440)
    * **Machine Learning:** Multimodal Machine Learning (11-777), Convex Optimization (10-725), Advanced NLP (11-711), Advanced Deep Learning (10-707)
    * **Maths:** Methods of Optimization (21-690), Numerical Linear Algebra (21-344), Principals of Real Analysis (21-356)
    
Teaching
======
* **Teaching Assistant** for 15-213/513 Introduction to Computer Systems, Summer 2023, CMU
* **Teaching Assistant** for 10-701 Introduction to Machine Learning (Ph.D.), Fall 2023, CMU
* **Teaching Assistant** for 15-712 Advanced Operating Systems and Distributed Systems, Fall 2023, CMU

Research Experiences
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

Entrepreneurship
======
* **[QI-Algorithms]**
  * **Duration:** Jul. 2022 - Present
  * **Title:** Co-founder & Lead Technical Support
  * **Collaborators:** Chinese Academy of Science, Wuhan University Taikang Medical School (School of Basic Medical Science), Gannan Medical University
  * **Keywords:** AI Medical Care, Full-stack software development, Home IoT
  * **Our Motivation:**
    * Over the course of my academic endeavors, I realized that there’s an increasingly urgent need to allow the personalization of state-of-the-art AI models on light-weight computing platforms. Driven by this motivation, I co-founded a startup QI-Algorithms in Chongqing, China, with two of my friends. We started from an under-informationized but rapidly growing market, the pet-healthcare business. We aim to build an IoT platform gathering information from all pet devices with electronic sensors in the house, such as cameras, electronic collars, and feeders. I aim to fine-tune cutting-edge large models based on the data to perform animal-behavior learning and provide personalized medical advice for pet-owners. The personalized large model for each consumer would be based on years of private data collected from various devices. In order to achieve fine-tuning locally to ensure data privacy and reduce cloud computing cost, we need to be able to personalize AI on commodity hardware platforms or even edge devices. Currently, we’ve already designed a smart collar that could provide real-time movement recognition based on 6-axis gyroscope data. We’re also working with Professor Hongliang Li from Wuhan University to build a clinical dataset for sustaining animal disease forecasting. We're currently developing a smart database capable of managing enormous amounts of medical diagnoisis data and provide big-data-driven AI diagnoisis support for doctors and pet owners, as well as providing P2P recommendation from business owners to pet service consumers. I hope to explore the direction of sustaining memory efficient training and inference of large models on light-weight platforms in my future endeavour to make cutting-edge AI eventually personalizable.
  * **What we're currently doing:**
    * Building a LSTM neural network based on 6-axis accelerometer data from pet smart collars for real-time action tracking, expected to enter the market in March
    * Developing multimodal MedicalGPT for auto-diagnosis of animal diseases, in collaboration with 100+ researchers, primitive version expected to be released in March
    * Partnering with local investors to raise funds to build a machine learning laboratory for large model fine-tuning

ONGOING Projects
======
* **DAO: Dynamic Activation & Offloading**
  * **Duration:** Oct. 2023 - Present
  * **Supervisor:** Prof. Phillip Gibbons, Computer Science Department, CMU
  * **Keywords:** AI systems, Machine Learning, C++, Python
  * **Objective:**
    * Construct an AI framework capable of sustaining large model fine tuning on commodity hardware platform
    * Explore combining model stochastic depth with system level optimizations to save memory.
    * Design a more efficient memory management policy that dynamically offloads kernel executions from GPU to CPU memory
  * **Brief Introduction:**
  * Our research aimed to resolve the lack of frameworks capable of sustaining fine-tuning of dynamic large neural networks on commodity hardware platforms, an obstacle that greatly limits the democratization of personalized AI. Existing works such as Zero-offload utilize fixed offloading policy by moving optimization stages from GPU to CPU memory, and therefore couldn’t handle control-flows in network architectures. To tackle this problem, I’m currently designing an “on-the-fly” CPU-GPU memory manager capable of deciding placement of each tensor depending on future memory access patterns, taking advantage of my knowledge in data structures and scheduling algorithms. Using a combination of model level optimizations such as stochastic depth and system level optimizations such as memory offloading, we aim to fine-tune large language models such as Llama 7B on light-weight platforms. Based on our initial evaluations, we expect our framework to save significant amounts of GPU memory compared to PyTorch, without sacrificing much computational throughput. After finishing our milestone, we also plan to scale-up our current framework to support memory-efficient training of large models on distributed heterogeneous device platforms.


Past Projects
======
* **[Efficient clustering and spectral library search under large data scale](https://github.com/mohimanilab/MASSTplus)**
  * **Duration:** AUG. 2021 - JUL. 2023
  * **Support:** awards from [NSF 2117640](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2117640&HistoricalAwards=false), U.S. Department of Energy [DE-SC0021340](https://pamspublic.science.energy.gov/WebPAMSExternal/Interface/Common/ViewPublicAbstract.aspx?rv=a601ce84-b365-4772-87d3-9ee13d943635&rtc=24&PRoleId=10)
  * **Supervisor:** Dr. Hosein Mohimani, Computational Biology Department, CMU
  * **Keywords:** C++, Rust, Algorithms, Data mining, Software Engineering, Biostatistics
  * One of the main contributors for designing and implementing MASST+ & Networking+, two toolkits for large-scale spectral library clustering, searching and analysis that’s three orders of magnitudes faster than the state of art
  * Our contribution greatly improves the efficiency of natural product discoveries and genome mining
  * [Paper](https://www.nature.com/articles/s41587-023-01985-4) published in Nature Biotechnology
  
* **[Learning A-domain substrate specificities using AdenPredictor](https://github.com/MihirMongia/AdenPredictor)**
  * **Duration:** DEC. 2021 - OCT. 2022
  * **Support:** [NSF award 2117640](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2117640&HistoricalAwards=false)
  * **Supervisor:** Dr. Hosein Mohimani, Computational Biology Department, CMU
  * **Keywords:** Python, Machine Learning, Bioinformatics
  * Participated in developing AdenPredictor, a powerful toolkit for identifying bioactive compounds for drug discoveries.
  * Our tool predicts the binding of amino acids to A-domain protein subsequences using ensembled ML Models that incorporates 3-dimensional domain structures from AlphaFold2, achieving about 90% accuracy on testing data
  * [Paper](http://YudongL2000.github.io/files/adenPredictor.pdf) published on Bioinformatics
  
* **[High-Modality Multimodal Transformer](https://github.com/pliang279/HighMMT)**
  * **Duration:** JUN. 2022 - FEB. 2023
  * **Support:** Meta, [NSF award 1750439](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1750439&HistoricalAwards=false), [NSF award 1722822](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1722822&HistoricalAwards=false)
  * **Supervisor:** Dr. Louis-Philippe Morency, Language Technologies Institute, CMU
  * **Keywords:** Python, PyTorch, Deep Learning
  * Participated in the development of HighMMT, a model capable of handling over 8 modalities including spoken language, video, gestures, text and robot sensory data through few-shot modality transfer
  * Improved the tradeoff between performance and parameter-efficiency over existing state-of-art models
  * [Paper](http://YudongL2000.github.io/files/highMMT.pdf) published on TMLR
  
* **[DynPartition](https://github.com/YudongL2000/DynPartition)**
  * **Duration:** FEB. - MAY 2022
  * **Supervisor:** Prof. Philip Gibbons, Computer Science Department, CMU
  * **Keywords:** Python, Distributed Machine Learning, Distributed Systems
  * Proposed and implemented a novel rein-forcement learning-based scheduler that performs dynamic partitioning of computation workload across multiple heterogeneous GPUs for large neural network inference tasks
  * explored an important area of research in distributed machine learning under Cloud Cluster settings
  * [View our report here](http://YudongL2000.github.io/files/RL_scheduler.pdf)

* **[Distributed Bitcoin Miner](https://github.com/YudongL2000/Distributed_Bitcoin_miner)**
  * **Duration:** AUG. - OCT. 2020
  * **Supervisor:** Dr. Heather Miller, Computer Science Department, CMU
  * **Keywords:** Golang, Distributed Systems, Networking
  * Designed a mock distributed bitcoin miner based on Remote Procedural Calls (RPC) between client-server interactions
  * The miner runs on LSP (Live Sequence Protocol) capable of handling computational intensive tasks and recovering from sudden failure

* **Raft Consensus Algorithm**
  * **Duration:** OCT. - DEC. 2020
  * **Supervisor:** Dr. Heather Miller, Computer Science Department, CMU
  * **Keywords:** Golang, Distributed Systems, Networking
  * Implemented a Raft consensus algorithm to support concurrent accesses to a distributed database based on my 15440 course project.
  * I organized client requests into log for each replica to ensure agreement across different servers and
allow easy fault-recovery after server failure

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
  

