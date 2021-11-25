---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm [a 2nd-year cs phd student at Kim's lab](https://www.kimlab.org/members/people) in University of Toronto focusing on machine learning area.

---

machine learning has achieved rapid progress in many areasdue to its ability to understanding the comprehensive relationships between multiple interdependent variables. My research applies a wide range of deep learning approaches to better understand protein structure and function. I believe that the ability to design proteins shows our understanding of biology.

Over the past three years, I have developed several deep learning models for computational biology including CNN, LSTM, transformers, and deep generative model using Keras and Pytorch. Models have been demonstrated state-of-art performance, and papers are available in [publication section](https://xxiexuezhi.github.io/publications/).

<!-- 
Over the past few years, I have transitioned most of my computational research from a C-and-Matlab two-language workflow (C for heavy lifting / parallel work, and Matlab everything else) to a pure [Julia](https://julialang.org/) workflow, using [MPI.jl](https://github.com/JuliaParallel/MPI.jl) for most parallel/HPC work, along with packages like [LoopVectoriztion.jl](https://github.com/chriselrod/LoopVectorization.jl) and [VectorizedRNG.jl](https://github.com/chriselrod/VectorizedRNG.jl) for SIMD performance. I have written up a few [notes](https://github.com/brenhinkeller/JuliaAdviceForMatlabProgrammers) of advice for anyone else who is interested in doing the same. The short version: efficient _multiple dispatch_ really does provide a solution to the "two-language problem", but the dispatch-centric programming paradigm can take quite a while to fully internalize; beware _type instability_.

---

For mineral (especially zircon) eruption/deposition age estimation, there is a simple example in this [BayeZirChron demo notebook](https://mybinder.org/v2/gh/brenhinkeller/BayeZirChron.c/main?filepath=julia%2Fdemo.ipynb) based on [Keller, Schoene, & Samperton (2018)]( https://doi.org/10.7185/geochemlet.1826), or the [Chron.jl](https://github.com/brenhinkeller/Chron.jl) version of the same notebook:

* Standalone eruption/deposition age modelling
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/Chron.jl/main?filepath=examples/EruptionDepositionAgeDemonstration.ipynb)

While originally developed for zircon eruption age estimation, an analagous approach is also applicable to plutonic settings (e.g., [Ratschbacher et al., 2018](https://doi.org/10.1093/petrology/egy079)), or to the problem of finding the distribution of the limits of a highly dispersed mineral crystallization (or closure) age spectrum more broadly.

Other [Chron.jl](https://github.com/brenhinkeller/Chron.jl) example notebooks demonstrate the integration of this eruption/deposition approach with age-depth modelling, or standalone age-depth models.

* Coupled eruption-age and age-depth modelling
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/Chron.jl/main?filepath=examples/Chron1.0Coupled.ipynb)

* Age-depth modelling with simple Gaussian age constraints
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/Chron.jl/main?filepath=examples/Chron1.0StratOnly.ipynb)

* Age-depth modelling with radiocarbon age constraints
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/Chron.jl/main?filepath=examples/Chron1.0Radiocarbon.ipynb)


If you're interested in "statistical geochemistry", especially weighted bootstrap resampling of whole-rock geochemical data, try [StatGeochem.jl](https://github.com/brenhinkeller/StatGeochem.jl) (Julia), or else [StatisticalGeochemistry](https://github.com/brenhinkeller/StatisticalGeochemistry) (Matlab, no longer actively developed). A number of example usage notebooks are available in the StatGeochem.jl repo, including

* Weighted bootstrap resampling
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/StatGeochem.jl/main?filepath=examples/BootstrapResamplingDemo.ipynb)

* Julia-alphaMELTS interface demo
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/StatGeochem.jl/main?filepath=examples/MeltsExamples.ipynb)

* Julia-Perple_X interface demo
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/StatGeochem.jl/main?filepath=examples/PerplexExamples.ipynb)

* Constant-silica reference crustal model (see [Keller & Harrison, 2020](https://www.pnas.org/content/117/35/21101))
[![Binder](https://static.mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brenhinkeller/StatGeochem.jl/main?filepath=examples/ConstantSilicaReferenceModel.ipynb) -->

---
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


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
 
