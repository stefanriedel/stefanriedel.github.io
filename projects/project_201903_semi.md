---
layout: project
type: project
image: images/semi/thumb.jpg
title: Semi-Parametric Learning with Bayesian NNs and GPs
permalink: projects/semi
# All dates must be YYYY-MM-DD format!
date: 2019-03-01
labels:
  - Python
  - C++
  - Research
  - Machine Learning
  - Tensorflow
summary: Implementation and evaluation of different semi-parametric machine learning approaches.
---

<!--<a href="https://raw.githubusercontent.com/SebastianRiedel/sebastianriedel.github.io/master/images/logview/logview.png" class="ui large right floated rounded image">
  <img src="../images/template_thumb.jpg">
</a>

This should be a one or two sentence introduction to what the project is about and what the goal was. A bit more would be good for better formatting and that the next headline is full width. I can even add a third sentence so which explain why this is important or what I gained from this project in terms of lessons learned or what I found interesting about it.-->

<img class="ui fluid bordered image" src="../images/semi/bar_plot_via_rmse.png">

We evaluated semi-parametric Gaussian process regression (SPGP) and a novel model-based neural network architecture (BaMbAnn), and compared their modeling accuracy to a series of naive semi-parametric, parametric-only and non-parametric-only regression methods. The comparison has been carried out on three test scenarios, one involving a real test-bed and two involving simulated scenarios, with the most complex scenario targeting the modeling a simulated robot’s inverse dynamics model.

### Further Material
- [1] Technical Report: Sebastian Riedel, and Freek Stulp. <a href="https://drive.google.com/open?id=1Pij_EJf6DaEHA-z5PHdUaQy_io5_LHLi">"Comparing Semi-Parametric Model Learning Algorithms for Dynamic Model Estimation in Robotics"</a> [Draft]

<hr>
**Technology Stack:** Python, Tensorflow, Scikit-Learn, C++, Limbo

**Work Affiliation:** German Aerospace Center (DLR)
