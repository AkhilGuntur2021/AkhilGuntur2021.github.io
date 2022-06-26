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
* B.Tech. in Electronics and Communications Engineering, Manipal Institute of Technology, Manipal, India (July 2015 - May 2019)
* M.S. in Electrical and Computer Engineering, Carnegie Mellon University, Pittsburgh, PA (May 2020 - August 2020)
* M.S. in Electrical and Computer Engineering, Purdue University, West Lafayette, IN (August 2021 - Dec 2022)


Work experience
======
* July 2019 - July 2021: Project Engineer, Wipro Technologies Ltd., Pune, India
  * Extensive experience in Analysis, Design, Development, and Implementation of applications with thorough hands-on experience on flask framework, MVC architecture,       Apache-Tomcat, CRUD Operations, MongoDB, SQL, Gradle. 
  * Built authentication module by processing client’s employee ID cards using OpenCV and Tesseract OCR, with a 27% improved accuracy over the previous solution.
  * Built claim form recognition module using OpenCV and Azure Form Recognizer cognitive service, which eliminated the need for time-consuming manual review. 
  * Worked on virtual call auditor platform to automate the audit of customer-service rep transcripts using flask, MongoDB, Spacy models, and fasttext AI for effective     analysis of customer sentiment and experience, which improved the call audit efficiency by 70%. 
  * Built a claim document classification model using image processing (OpenCV, PIL), OCR (Azure), and NLP (Scikit-learn, NLTK, Tensorflow).
  * Setup and maintained Linux and Windows based servers for various backend services.


* Jan 2019 - May 2019: Senior Year Thesis, Manipal Institute of Technology, Manipal, India
  * Built ARMA models with multiple orders ranging from 4 to 9 on RRI data and performed Empirical Mode Decomposition (EMD) to extract Intrinsic Mode Functions (IMFs)     for each RRI signal.
  * Built neural networks with algorithms such as L-BFGS, RMSProp to solve the classification problem for the two methods (ARMA and EMD).
  * Performed comparison analysis of three methods (Recurrence Analysis, ARMA, and EMD) to conclude on the suitability of each technique for each phase and its             implications on Cardiac Autonomic Regulation alteration.

* May 2018 - July 2018: Research Intern, National Institute of Technology, Rourkela, India
  * Extracted RR intervals from the ECG signals through a custom-made algorithm (using bandpass filtering, derivation, squaring, moving window integrator, and peak         detection).
  * Applied Recurrence Analysis and assessed the Recurrence Plots of each menstrual phase data.
  * Found statistically significant features through statistical tests such as t-tests and decision tree strategies such as CARTs, Boosted Trees (BT), and Random           Forests (RF) and used neural networks with algorithms such as Levenberg–Marquardt (LM) to perform classification in MATLAB software to correlate cardiac activity       and smoking.



  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
