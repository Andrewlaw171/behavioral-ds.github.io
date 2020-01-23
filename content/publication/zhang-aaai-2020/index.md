---
title: "Variational Inference for Sparse Gaussian Process Modulated Hawkes Process"
date: 2020-01-01
publishDate: 2019-12-29T23:55:04.469442Z
authors: ["Rui Zhang", "Christian Walder", "Marian-Andrei Rizoiu"]
publication_types: ["1"]
abstract: "The Hawkes process (HP) has been widely applied to modeling self-exciting events including neuron spikes, earthquakes and tweets. To avoid designing parametric triggering kernel and to be able to quantify the prediction confidence, the non-parametric Bayesian HP has been proposed. However, the inference of such models suffers from unscalability or slow convergence. In this paper, we aim to solve both problems. Specifically, first, we propose a new non-parametric Bayesian HP in which the triggering kernel is modeled as a squared sparse Gaussian process. Then, we propose a novel variational inference schema for model optimization. We employ the branching structure of the HP so that maximization of evidence lower bound (ELBO) is tractable by the expectation-maximization algorithm. We propose a tighter ELBO which improves the fitting performance. Further, we accelerate the novel variational inference schema to linear time complexity by leveraging the stationarity of the triggering kernel. Different from prior acceleration methods, ours enjoys higher efficiency. Finally, we exploit synthetic data and two large social media datasets to evaluate our method. We show that our approach outperforms state-of-the-art non-parametric frequentist and Bayesian methods. We validate the efficiency of our accelerated variational inference schema and practical utility of our tighter ELBO for model selection. We observe that the tighter ELBO exceeds the common one in model selection."
featured: false
publication: "*AAAI Conference on Artificial Intelligence (AAAI)*"
---
