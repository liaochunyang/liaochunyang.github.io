---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are Approximation Theory, High-dimensioanl Probability, and in particular their applications in Scientific Machine Learning and Data Science.

## Optimal Recovery ##

Optimal Recovery (OR), which is a subfield of Approximation Theory, can be viewed as a nonstatistical learning Theory. The main task is to approximate an unknown function from observations and an explicit model assumption on the function to be recovered. The problem is considered under deterministic problem setting where we assume function inputs are fixed quantities (even unfavorable) and observational errors are bounded not random. To assess the performance, we adopt worst-case error perspective which is key to Optimal Recovery. 

We observed that the optimal recovery framework has a closed relation to Learning Theory, Numerical Analysis (Quadrature Rule), Gaussian Process Regression and Estimation Theory. It has been used to explain many practical problems, but the development of optimal recovery slowed down due to the lack of computational advantages.

**Worst-Case Error:**
```math
\inf_{\phi:\mathbb{R}^m\to\mathcal{H}} \sup_{ \substack{ f\in\mathcal{K} \\ \|e\|\leq\eta} } \| Q(f) - \phi(\Lambda(f)+e) \|
```

**The goal of my research is to make optimal recovery more computational-embracing.** Some recent papers with reproducible files can be found [here](https://github.com/liaochunyang/Optimal_Recovery). 

## Scientific Machine Learning ##

Scientific machine learning (SciML) is a a rapidly merging field where people apply machine learning techniques to solve complex problems in science and engineering. 
It bridges the gap between traditional approaches that rely on explicit physical laws, and modern machine learning techniques that derive patterns from data. 
**The goal of my research is to provide theoretical analysis on various machine models and to develop efficient numerical method for various scientific machine learning problems.**
