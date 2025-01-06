---
layout: default
title: Custom-Metaheuristic-Population-Based-Optimizer
permalink: /custom--metaheuristic-population-based-optimizer
date: 2023-11-23
categories: research
excerpt: An investigation into custom-made neural network optimizers. 
repo_link: https://github.com/SurtMcGert/Custom-Metaherusitic-Population-Based-Optimizer
---

# What?
As part of a final-year project in our Computer Science BSc degree, we (a group of three students) conducted research into the feasibility of metaheuristic, population-based optimizers. We created implementations of existing algorithms, namely the *Genetic Algorithm*, *Bat Optimization Algorithm*, and *Grey Wolf Optimization Algorithm*, compared their effectiveness, then subsequently desgined our a custom optimizer based on our findings.

# Why?
At this point in our degree, we had been learning about Artificial Intelligence for well over a year - being taught how to use libraries such as TensorFlow, Keras, and Pytorch to construct models at a high level. And while we understood the concepts we apply in our courseworks, there were many processes that we, at that point, had not delved into at a technical level - one of these being the application of optimizers. Using existing ones such as Adam and Gradient Descent works well and allows for a smooth, uninterrupted model-creation experience, but drifts over one of the most interestingly important aspects of how the model functions.

Conducting this research provided us with a deeper understanding of the lower-level functionalities behind neural networks.

# How?
A neural network was created and trained using the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html){:target="_blank" rel="noopener noreferrer"}. Retraining last layer of the model, we implemented our custom-made optimziers. Evaluations were made using the loss and accuracy metrics, and our findings were collated in a report.
