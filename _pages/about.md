---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


Welcome to my personal website !

I am [a 4th-year cs phd student at Kim's lab](https://www.kimlab.org/members/people) at the University of Toronto, specializing in AI for science. My research focuses on using generative AI to design pharmaceutical peptide and protein drugs, with projects including D-peptide drugs and epitope-specific antibodies for applications such as wet-lab validated GLP-1 agonists and SARS-CoV-2 treatments.

---

My work involves in integrating computational and experimental approaches to tackle critical biomedical problems. Over the past three years, I have developed various deep learning models for computational biology, including flow-matching models, score-based diffusion models, generative adversarial networks, transformers, and reinforcement learning, using PyTorch and TensorFlow. I apply these cutting-edge gnerative AI to design and validate novel therapeutics, aiming to significantly impact patient care and therapy development.

Check out [my publication page](https://xxiexuezhi.github.io/publications/) for more details. 


---


<p align="left">
Check out the Recorded Virtual Talk on MLSB NeurIPS (HelixGAN) and Designed Cover for ACS Science (HelixDiff)
</p>
<p align="center">
<img src="/images/helixgan_nips_talk.png" width="40%"/>
  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; 
<img src="/images/acs_cover.jpg" width="37%"/>   
</p>





<p align="left">
Check out Our Designed Art Work Using Machine Learninig Which Was Selected as Cover Figure for ACS Science (IF 18,7) and the Recorded Virtual Talk on MLSB NeurIPS (HelixGAN)
</p>
<p align="center">
<a  href="https://pubs.acs.org/toc/acscii/10/5" target="_blank">
<img src="/images/acs_cover.jpg" width="37%"/>  
  &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp;&nbsp;  
<a href="https://slideslive.com/38971343/helixgan-a-generative-adversarial-network-with-search-in-latent-space-for-generation-under-constraints?ref=speaker-93539" target="_blank">  
<img src="/images/helixgan_nips_talk.png" width="39%"/>
  
</p>



---


<p align="left">
Check out my recent work on Flow-matching model using E3NN. the Gif for Flow-matching Process inide HelixFlow Model (14, 16, 18, 20 AA)
</p>



<p align="center">
<img src="/images/run_1_time_rosetta2.gif" width="25%"/>
&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;&nbsp; 
<img src="/images/a_font30_gif_len16.gif" width="40%"/> 
</p>
<p align="center">
<img src="/images/a_length18_gif.gif" width="40%"/>
&nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp;
<img src="/images/a_len20_image.gif" width="40%"/> 
</p>

<!-- 

The ability to design biological molecules shows our understanding of biology. My research interest mainly focuses on understanding biological systems and design for pharmaceutical peptide/protein drugs using generative AI. In particular, I’ve been focusing on the generation of the D-peptide drug and epitoipe-specific antibodies with different deep generative models and its applications to real-world tasks, for example, glucagon-like peptide 1 (GLP-1) agonists, SARS-CoV-2, etc. 

Over the past three years, I have developed mutiple deep learning models for computational biology including scored-based diffusion model, Generative adversarial network, transformers, and reinforcement learning using Pytorch and Tensorflow. Related papers are available in [publication section](https://xxiexuezhi.github.io/publications/).

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

Xuezhi Xie
======
PhD student, Department of Computer Science, University of Toronto
<br/><br/>


Education
======
* Ph.D in Computer Science, University of Toronto, 2020 - 2024 (expected)
* M.S. in Computer Science, specialization in Artificial Intelligence, Western University, 2018 - 2020
* B.S. in Biology, Minor in Computer science, University of Waterloo, 2012 - 2016
  
Skills
======
* Languages:  Java, Python, C, C#,  C++, JavaScript    
* Software:   Eclipse, Jupyter, Visual Studio/Code        
* Database:  SQL, MongoDB    
* Frameworks:  Keras, Pytorch, Tensorflow, PySpark, Hadoop MapReduce     
* System: Linux, Windows       
* Version Control: Git/GitHub
* Machine learning: Proficient in deep generative models (diffusion models, gan, VAE), CNN, LSTM, logistic regression, support vector machine, decision tree, random forest, GBDT,  naive bayes,  k-means, PCA, collaborative filtering. 
* Computer vision:  Skilled in image processing (OpenCV), object detection, object segmentation, mapping and localization, and SLAM.
* Natural language processing:  Skilled in text classification, sentiment analysis and speech recognition


Work experience
======
* Research assistant (machine learning) - University of Toronto, Toronto, On, Canada, 2020 - present
  * Developed different deep generative model for target-pecific drug design, including score-based diffusion model, GAN, and VAE.
  * Developed and implemented various searches and inpainting methods to optimize the synthetic data with optimized pharmetutical properties. 
  * Supervisor: Professor Philip M. Kim

* AI developer & Research assistant  - Kaizhong’s lab, Western University,  London, On, Canada, Sep.2018 - Apr. 2020
  * Collected peptide data from online databases (IEDB, IPD-MHC). Preprocessed, and analyzed data by using PySpark
  * Implemented and compared decision tree- and neural network-based models for predicting peptide binding.
  * Designed and developed a novel CNN-LSTM model to solve a mhc-ligand binding classification task. Achieved state of the art performance (AUC : 92.3%).
  * Published the work as first author in IEEE-BIBM (2019) and  IJDMB(2020).
  * Supervisor: Professor Kaizhong Zhang

Projects
======
* Diffusion model for antigen-specific antibody design           (Jan.2022 - now)
  * Developed a score-based diffusion model named AntibodySGM for antigen specefic antibody design and achived state-of-art performance compared with current deep learning models. 
  * Developed and implemented a novel CDR-inpainting module for antigen-specific antibody optimization. Published the work as first author in ICML Workshop (ICML computational biology) 2023. [Link for my paper](https://icml-compbio.github.io/2023/papers/WCBICML2023_paper143.pdf)
  * Create an online visulization tools for peptide and protien. Generated antiboy data also included. [Link for my visulization tool](https://huggingface.co/spaces/xxie92/proteinml-demo-dssp-duplicate) 



* Deep generative model with constraints for D-peptide drug design           (Jan.2019 - Jan.2023)
  * Developed a deep generative model using GAN for novel dextrorotary helical conformations to facilitate the peptide drug design.
  * Developed and implemented various latent search methods for the synthetic data with optimized pharmetutical properties. Published the work as first author in both Bioinformatics (2023) [Link for my paper](https://academic.oup.com/bioinformatics/article/39/1/btad036/6991169) and  NeuIPS Workshop (MLSB) 2021. [Link for my talk](https://recorder-v3.slideslive.com/?share=54078&s=518da677-492e-4627-96ce-c0190976326c)


* Cell detection application for pathological image analysis                  (Jan.2019 - April.2020)
  * Designed and developed customized object detection algorithms to detect brain cells and mitosis cells on pathology segmented images and whole slide images by using deep Convolutional Neural Network.
  * Designed and developed Ki-67 cell segmentation and detection algorithm based on cellpose  and image classification.
  
* Recommendation system for  prediction of user purchase behavior             (Jan. 2019 - Mar.2019) 
  * Classified data as train sets, validation sets and test sets. Constructed features using Pandas. Dealt with positive and negative sample imbalances using k-means and subsample.
  * Used the Gradient Boosting Decision Tree to predict user purchase behavior through model training, parameter tuning and performance evaluation using F1-Score. Ranked 4th in 135 submission teams ([Kaggle leaderboard link](https://www.kaggle.com/c/csc2515-rating-prediction/leaderboard))
  
  
* Data Mining for Twitter Unstructured Data                                   (Sep.2018 - Dec.2018)
  * Mining interesting information from twitter tweets (JSON). Operated complex and unstructured data using MongoDB. Used MapReduce to process and summarize information. Conducted ElasticSearch. Visualized the information using Kibana.
  


Publications 
======
(jourals)

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
(Conferences & workshops)
  <ul>{% for post in site.publications.conference reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Teaching
======



 -->
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
 
