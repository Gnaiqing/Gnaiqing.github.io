---
title: "Estimating regression predictive distributions with sample networks"
collection: publications
category: conferences
permalink: /publication/2023-samplenet
date: 2023-06-26
venue: 'the 37th AAAI Conference on Artificial Intelligence (AAAI)'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/25948'
---
**Nonparametric uncertainty estimation for deep neural networks with sample network.**

Estimating the uncertainty in deep neural network predictions is crucial for many real-world applications. A common approach to model uncertainty is to choose a parametric distribution and fit the data to it using maximum likelihood estimation. The chosen parametric form can be a poor fit to the data-generating distribution, resulting in unreliable uncertainty estimates. In this work, we propose SampleNet, a flexible and scalable architecture for modeling uncertainty that avoids specifying a parametric form on the output distribution. SampleNets do so by defining an empirical distribution using samples that are learned with the Energy Score and regularized with the Sinkhorn Divergence. SampleNets are shown to be able to well-fit a wide range of distributions and to outperform baselines on large-scale real-world regression tasks.
