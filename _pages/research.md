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

| | Linear recovery | Arbitrary recovery |
|---|---|---|
| Linear information <br>(point evaluation) | Approximation number  | Gelfand width <br>(Sampling number) |
| Arbitrary information | Linear width | Manifold width |


We observed that the optimal recovery framework has a closed relation to Learning Theory, Numerical Analysis (Quadrature Rule), Gaussian Process Regression and Estimation Theory. It has been used to explain many practical problems, but the development of optimal recovery slowed down due to the lack of computational advantages.

**The goal of my research is to make optimal recovery more computational-embracing.** Some recent papers with reproducible files can be found [here](https://github.com/liaochunyang/Optimal_Recovery). 


## Scientific Machine Learning

Scientific machine learning (SciML), which is a rapidly emerging field, combines data-driven methods with traditional scientific modeling to solve complex physical and engineering problems.
It bridges the gap between traditional approaches that rely on explicit physical laws, and modern machine learning techniques that derive patterns from data. 

I am interested in the **theoretical foundations** of Scientific Machine Learning and the development of **novel computational methods** that are reliable, efficient, and broadly applicable across scientific domains.
Some recent work with reproducible files and public resources can be found [here](https://github.com/liaochunyang/SciML).

### Physics-informed Machine Learning
Physics-informed Machine Learning (PIML) is an approach that integrates physical laws and governing equations directly into data-driven models. By combining the flexibility of machine learning with the structure and interpretability of physical principles, PIML can enable more accurate, robust, and physically consistent predictions. 

One example is the use of physics-informed neural networks (PINNs) to solve partial differential equations (PDEs). Instead of relying solely on large amounts of labeled simulation data, a neural network can be trained while enforcing the underlying PDE, together with its initial and boundary conditions, as part of the learning objective. This provides a way to approximate solutions to complex physical systems directly from their governing equations.

**My goals are developing theoretical foundation that explains its approximation, optimization, and generalization properties, designing efficient, reliable, and principled computational methods, and applying them to challenging real-world problems.**

### Operator Learning
Operator learning focuses on learning mappings between infinite-dimensional function spaces, rather than conventional mappings between finite-dimensional inputs and outputs. A representative example is learning the solution operator of a partial differential equation (PDE), which maps input functions such as initial conditions, boundary conditions, or source terms to the corresponding PDE solutions.

This ambitious framework provides a powerful approach for learning families of PDE solutions and can enable efficient surrogate models for repeated simulations across varying initial conditions, parameters, and physical settings.

My research focuses on developing the theoretical foundations of operator learning, understanding its approximation, generalization, and computational properties, and designing novel and efficient operator-learning methods that are reliable across different physical systems and problem settings. Ultimately, I aim to develop principled operator-learning approaches that combine mathematical theory with computational efficiency and enable applications to challenging problems in scientific computing.
