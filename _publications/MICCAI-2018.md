---
title: "Uncertainty Estimation in Segmentation with Perfect MCMC Sampling in Bayesian MRFs"
collection: publications
permalink: /publication/MICCAI-2018
authors : "Saurabh Garg, Suyash Awate" 
venue: 'Proceedings of Medical Image Computing & Computer Assisted Intervention (MICCAI), 2018'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-00928-1_76' 
---

Typical segmentation methods produce a single optimal so- lution and fail to inform about (i) the confidence / uncertainty in the object boundaries or (ii) alternate close-to-optimal solutions. To estimate uncertainty, some methods intend to sample segmentations from an asso- ciated posterior model using Markov chain Monte Carlo (MCMC) sam- pling or perturbation models. However, they cannot guarantee sampling from the true posterior, deviating significantly in practice. We propose a novel method that guarantees exact MCMC sampling, in finite time, of multi-label segmentations from generic Bayesian Markov random field (MRF) models. For exact sampling, we propose Fill’s strategy and extend it to generic MRF models via a novel bounding chain algorithm. Results on simulated data and clinical brain images from 4 classic problems show that our uncertainty estimates gain accuracy over the state of the art.
