---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Xuezhi Xie
---
PhD student, Department of Computer Science, University of Toronto
<br/><br/>


Education
======
* B.S. in Biology, Minor in Computer science, University of Waterloo, 2012 - 2016
* M.S. in Computer Science, specialization in Artificial Intelligence, Western University, 2018 - 2020
* Ph.D in Computer Science, University of Toronto, 2020 - 2024 (expected)

Work experience
======
* Research assistant (machine learning) - University of Toronto, Toronto, On, Canada, 2020 - present
  * Developed a deep generative model for novel dextrorotary helical conformations to facilitate the peptide drug design.
  * Developed and implemented various MCMC searches to optimize the synthetic data with optimized pharmetutical properties. Published the work as first author in NeuIPS Workshop (MLSB) 2021.
  * Pre-trained a graph convolutional network to reconstruct masked amino acids in proteins
  * Supervisor: Professor Philip M. Kim

* AI developer & Research assistant  - Kaizhong’s lab, Western University,  London, On, Canada, Sep.2018 - Apr. 2020
  * Collected peptide data from online databases (IEDB, IPD-MHC). Preprocessed, and analyzed data by using PySpark
  * Implemented and compared decision tree- and neural network-based models for predicting peptide binding.
  * Designed and developed a novel CNN-LSTM model to solve a mhc-ligand binding classification task. Achieved state of the art performance (AUC : 92.3%).
  * Published the work as first author in IEEE-BIBM (2019) and  IJDMB(2020).
  * Supervisor: Professor Kaizhong Zhang
  
Skills
======
* Languages:  Java, Python, C, C#,  C++, JavaScript    
* Software:   Eclipse, Jupyter, Visual Studio/Code        
* Database:  SQL, MongoDB    
* Frameworks:  Keras, Pytorch, Tensorflow, PySpark, Hadoop MapReduce     
* System: Linux, Windows       
* Version Control: Git/GitHub
* Machine learning: Proficient in deep Convolutional Neural Network, LSTM, logistic regression, support vector machine, decision tree, random forest, GBDT,  naive bayes,  k-means, PCA, collaborative filtering. 
* Computer vision:  Skilled in image processing (OpenCV), object detection, object segmentation, mapping and localization, and SLAM.
* Natural language processing:  Skilled in text classification, sentiment analysis and speech recognition

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
 
