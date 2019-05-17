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

<img class="ui fluid bordered image" src="../images/semi/bar_plot_via_rmse.jpg">

We evaluated semi-parametric Gaussian process regression (SPGP) and a novel model-based neural network architecture (BaMbAnn), and compared their modeling accuracy to a series of naive semi-parametric, parametric-only and non-parametric-only regression methods. The comparison has been carried out on three test scenarios, one involving a real test-bed and two involving simulated scenarios, with the most complex scenario targeting the modeling a simulated robot’s inverse dynamics model.

### Further Material
- [1] Technical Report: Sebastian Riedel, and Freek Stulp. <a href="https://drive.google.com/open?id=1Pij_EJf6DaEHA-z5PHdUaQy_io5_LHLi">"Comparing Semi-Parametric Model Learning Algorithms for Dynamic Model Estimation in Robotics"</a> [Draft]

<hr>
**Technology Stack:** Python, Tensorflow, Scikit-Learn, C++, Limbo

**Work Affiliation:** German Aerospace Center (DLR), in collaboration with Florian Loeffl
