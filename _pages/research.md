---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research interests are Approximation Theory, Scientific Machine Learning， and Mathematical Data Science. In particular, I am working on the following problems：

## Optimal Recovery

Optimal Recovery (OR), which is a subfield of Approximation Theory, can be viewed as a nonstatistical learning Theory. The main task is to approximate an unknown function from observations and an explicit model assumption on the function to be recovered.

$$
\text{Function Space } F \overset{N}{\longrightarrow} \mathbb{R}^n \overset{\varphi}{\longrightarrow} \text{Target Space } Z
$$

The problem is considered under deterministic problem setting where we assume function inputs are fixed quantities (even unfavorable) and observational errors are bounded not random. To assess the performance, we adopt worst-case error perspective which is key to Optimal Recovery:

$$
\inf_{\varphi} \sup_{f\in \mathcal{K}} \| Q(f) - \varphi(N(f)) \|_Z
$$

Beyond the general setting described above, we may also consider several more specific settings in which either the information $N$ or the recovery method $\varphi$ is restricted to be linear. Some of these settings are closely related to classical approximation theory, as summarized in the table below.

<div align="center">

<table>
  <tr>
    <th><font size="2">Information / Recovery</font></th>
    <th><font size="2">Linear recovery</font></th>
    <th><font size="2">Arbitrary recovery</font></th>
  </tr>
  <tr>
    <td><font size="2">Linear information</font></td>
    <td><font size="2">Approximation number</font></td>
    <td><font size="2">Gelfand number</font></td>
  </tr>
  <tr>
    <td><font size="2">Arbitrary information</font></td>
    <td><font size="2">Linear width</font></td>
    <td><font size="2">Manifold width</font></td>
  </tr>
</table>

</div>




We observed that the optimal recovery framework has a closed relation to Learning Theory, Numerical Analysis (Quadrature Rule), Gaussian Process Regression and Estimation Theory. It has been used to explain many practical problems, but the development of optimal recovery slowed down due to the lack of computational advantages.

**The goal of my research is to make optimal recovery more computational-embracing.** Some recent papers with reproducible files can be found [here](https://github.com/liaochunyang/Optimal_Recovery). 


## Scientific Machine Learning

Scientific machine learning (SciML), which is a rapidly emerging field, combines data-driven methods with traditional scientific modeling to solve complex physical and engineering problems.
It bridges the gap between traditional approaches that rely on explicit physical laws, and modern machine learning techniques that derive patterns from data. 
**My work focuses on the theoretical foundations and computational methods that make these approaches reliable, efficient, and broadly applicable across scientific domains.**

#### Physics-informed Machine Learning

#### Operator Learning

Operator learning focuses on learning mappings between function spaces rather than finite-dimensional inputs and outputs, see, for example, the solution operator from initial conditions to PDE solutions. 
This approach is particularly powerful for accelerating simulations of physical systems and enables rapid generalization across varying conditions.
