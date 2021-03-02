---
permalink: /
title: "William(Peijian) Ding"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


### Research Interests 
Scientific Computing, Numerical Analysis, Machine Learning, Optimization, and Inverse Problems 

### About Me
I am a undergraduate student double majoring in Applied Math & Statistics and in Computer Science at Emory University. I am currently working on my honors thesis with [Dr. James Nagy](http://www.mathcs.emory.edu/~nagy/) in the [Emory Scientific Computing Group](http://www.mathcs.emory.edu/Research/Area/ScientificComputing/). It's a nonlinear least square problem arising from medical imaging applications. I was a data science [research fellow](http://www.quantitative.emory.edu/about/fellows/index.html#collapse3) working on an interdisciplinary research topic in political science and data science with [Dr. Holli Semetko](http://polisci.emory.edu/home/people/biography/semetko-holli.html) in my junior year in the Department of Quantitative Theory and Methods. The data science part mostly involved [web-scraping](https://github.com/willding123/SinaWeiboScraper) and unsupervised learning. Currently, I am also a student in Emory's computational linguistic class doing project on training neural networks to rate privacy scores of social media companies and conducting linguistics analytics such as categorization (unsupervised learning) of privacy issues, keyword identification, and cross-lingual word embeddings.  

### Current Project Introduction 
While CT images can help diagonose coronavirus, the machines are big and expensive. We want to compensate for cheaper, more portable machines by solving for geometry parameters, like source-to-object distance, that may not be precisely callibrated during the imaging process. This is a optimization problem that invovles solving both linear (image) and nonlinear (geometry parameters) simultaneously. I adopted Block Coordinate Descent which sovles for image and geometry parameters respectively. The methods converges very fast on small test problems and show better results than solving linear system directly without considering the geometries.  By exploiting separability in the geometry parameters, I have increased the speed 4-5 times (without parallel computing). This matrix structure also allows us to have faster computing speed than using Variable Projection. I have implemented algorithms to accelerate the convergence such as the Accelerated Block Coordinate Descent and Anderson Acceleration. I am currently investigating the rank deficient issues incurred in the linear unconstrained problem during the Anderson Acceleration process. 

