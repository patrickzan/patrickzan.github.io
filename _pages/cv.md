---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
[Here](http://patrickzan.github.io/files/resume.pdf)'s a PDF version of my CV.
{% include base_path %}

Education
======
* B.S. in Electrical Engineering, Xi'an Jiaotong University, 2014
* M.S. in Electrical and Computer Engineering, University of Mayrland, College Park, 2019
* Ph.D in Electrical and Computer Engineering, University of Maryland, College Park, 2019

Work experience
======
* 02/2020 - Present: Principal Data Analytist (Scientist + Engineer)
  * Origin Wireless AI, Greenbelt, MD
  * WiFi-sensing for home security
    * Designed and optimized motion localization algorithm for WiFi-sensing devices.
    * Wrote Python tools for customers to process and visualize motion data.
    * Designed and automated a manufacture workflow by Python to build WiFi-sensing devices.
    * Reduced time consumption of building up one set of devices from about 40 min to 5 min.
    * Built 155 sets of devices for Verizon Communications Inc. to support their development and testing.
  * Real-time location tracking
    * Built an App using Python (Kivy and Buildozer) to track human location in real time based only on inertial measurement unit sensors from phone.
    * Optimized the tracking algorithm and achieved centimeter-level accuracy.
* 05/2019 - 08/2019: DSP Research Intern
  * Starkey Hearing Technologies, Eden Prairie, MN
  * DNN-based Speech Enhancement
    * Designed and conducted subjective listening experiment to test DNN-based speech enhancement algorithms.
    * Analyzed experimental data and compared DNN algorithms.
  * Joint Approach of Auditory Attention Decoding and Speech Enhancement
    * Designed and conducted electroencephalography (EEG) experiment to simulate a cocktail party scenario.
    * Collected auditory responses while subjects switch attention from one speaker to another.
    * Developed algorithm for joint approach of attention decoding and speech enhancement.
* 08/2015 - 05/2019: Graduate Research Assistant
  * University of Maryland, College Park, MD
  * Supervisor: Prof. Jonathan Z. Simon
  * Mutual Information Analysis of Auditory Brain Responses and Effects of Aging
    * Developed a novel approach based on information theory to decode phase-locked response from M/EEG recording.
    * Revealed speech over-representation in the aging midbrain [J1] and cortical [J2] marker of behaviors.
    * Algorithm programmed in Matlab, source-space analysis done in Python and statistics conducted in R.
  * Machine Learning Applications in Auditory Research
    * Implemented KNN and CNN for schizophrenia detection based on auditory steady-state response features.
    * Designed and compared neural decoders based on maximum likelihood estimation, linear regression and neural network to study adaptive efficient coding of correlated acoustic properties in auditory cortex of ferret.
    * Developed object and edge detection approach to extract pupillometry information from video recordings to study implicit memory for complex sounds in auditory cortex of ferret.
  
Skills
======
* Programming
  * Python
  * C/C++
  * R
  * Java
* Software Tools
  * Matlab
  * SPSS
  * MNE-Python
  * Eelbrain
  * Tensorflow
  * PyTorch
  * Latex
  * Git/Github
  * Linux/Unix
* Data Science
  * Statistics
  * Machine Learning
  * Deep Learning
* Data Engineering
  * Database
  * SQL
  * Google Cloud Platform
* Research
  * Auditory Neuroscience Exaperiment
  * Electroencephalography (EEG)
  * Magnetoencephalography (MEG)


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
  
Selected Awards & Honors
======
* Starkey Recognition Award, Starkey, 08/2019
* COMBINE Traveling Award, UMD, 12/2018
* NSF-Funded COMBINE Fellowship (Computational Biological Network Program), UMD, 09/2017
* Jimmy H. C. Lin Graduate Scholarship for Entrepreneurship, UMD, 09/2014
* ECE Ph.D. Fellowship Award, UMD, 09/2014
