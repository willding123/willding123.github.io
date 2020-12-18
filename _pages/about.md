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
Scientific Computing, numerical analysis, machine learning, optimization, and inverse problems 

### About Me
I am a undergraduate student double majoring in Applied Math & Statistics and in Computer Science at Emory University. I am currently with on my honors thesis with [Dr. James Nagy](http://www.mathcs.emory.edu/~nagy/) in the [Emory Scientific Computing Group](http://www.mathcs.emory.edu/Research/Area/ScientificComputing/). It's a nonlinear least square problem arising from medical imaging applications. I was a data science [research fellow](http://www.quantitative.emory.edu/about/fellows/index.html#collapse3) my junior year in the Department of Quantitative Theory and Methods. It was an interdisciplinary research topic in political science and data science, more specifically web-scraping and unsupervised learning. 

### Current Project Background 
While CT images can help diagonose coronavirus, the machines are big and expensive. We want to compensate for cheaper, more portable machines by solving for geometry parameters, like source-to-object distance, that may not be precisely callibrated during the imaging process. This is a optimization problem that invovles solving both linear (image) and nonlinear (geometry parameters) simultaneously. I adopted Block Coordinate Descent which sovles for image and geometry parameters respectively. The methods converges very fast on small test problems and show better results than solving linear system directly without considering the geometries. By exploiting separability in the geometry parameters, I have increased the speed 4-5 times (without parallel computing). I am working on Varible Projection method and investigating possible acceleration algorithms to speed up convergence. 


