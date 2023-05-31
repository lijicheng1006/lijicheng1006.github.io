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
* Ph.D. in Computer Science, University of Delaware. 2019 - Current <br/>
  Advisor: Roghayeh Barmaki
* M.S. in Computer Science, Michigan State University, 2019
* M.S. in Electrical Engineering, Northeastern University, 2016
* B.E. in Electrical Engineering, Harbin Institute of Technology, 2015

Skills
======
* Programming Languages: Python, Java, C++, MATLAB, SQL, R, Bash
* Libraries/Tools: PyTorch, TensorFlow, Keras, Sklearn, NumPy, SciPy, OpenCV, Pandas, OpenCL, AWS, Git, FFmpeg, LATEX

Experience
======
* Research Assistant, University of Delaware, Human-Computer Interaction Lab, Jun 2019 – Present
  * Developed systematic plans for dataset collection, problem definition, and solution development in multidisciplinary research using cutting-edge deep learning techniques for video understanding and human behavior analysis, with a focus on action quality assessment and intervention evaluation
  *	Established a large-scale, multimodal benchmark dataset comprising over 244K frames for behavior evaluation in autism research. Integrated diverse modalities including optical flow, skeleton, gaze, and clinician evaluation scores, one of the first publicly accessible datasets in the field
  *	Built deep learning methods that exclusively utilize privacy-preserving data, overcoming critical data-sharing challenges in sensitive research fields. Applied knowledge distillation to further enhance model performance and leverage video information without compromising privacy
  *	Designed a novel skeleton-based, uncertainty-aware Transformer Network to assess action quality while being robust to pose detection failures, demonstrating state-of-the-art performance on synchrony score prediction with a decrease in mean square error by 53.8% on the TASD-2 dataset
  *	Proposed an innovative two-stage affect states recognition framework that integrates facial expressions and acoustic cues, effectively leveraging the synergy between human expertise and machine intelligence

* Research Intern, Samsung Research America (Digital Health), Jan 2023 – Mar 2023
  * Developed an innovative evaluation metric to assess facial alignment in remote vital sign detection, one of the first works to provide comprehensive guidelines for optimal face detector selection in the field
  * Conducted experiments validating a 12.5% reduction in second-level mean absolute error and a 3.5% enhancement in accuracy for remote heart rate estimation by leveraging the superior face detector recommended by our metric

* Machine Learning Engineer, GENISAMA LLC, Jan 2017 – Aug 201
  * Developed optimized GPU kernels using OpenCL to accelerate the training and inference time of neural networks
  * Achieved an average 4x speedup compared to CPU runtime, leading to substantial efficiency improvements
  * Deployed the application on both PC and Android platforms, ensuring widespread accessibility and usability
  * Performed debugging, testing, and version updates to ensure smooth operation and integration of new features

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Honors And Awards
======
* CIS Distinguished Graduate Student Award, University of Delaware, 2020 – 2022
* Graduate Block Stipend Fellowship, University of Delaware, 2021
* Graduate Office Fellowship, Michigan State University, 2017
* Meritorious Winner at Science and Technology Innovation Contest, Harbin Institute of Technology, 2014

Patent
======
* Bluetooth module based access control system and access control method thereof
  * An innovative access control method of controlling a mechanical lock via MCU and mobile phone 
  * Publication number: CN103295303B 

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


<!--  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams
-->
