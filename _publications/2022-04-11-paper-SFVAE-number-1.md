---
title: "Learning and controlling the source-filter representation of speech with a variational autoencoder"
collection: publications
permalink: /publication/2022-04-11-paper-SFVAE-number-1
excerpt: 'We show that the source-filter model of speech production naturally emerges in the latent space of an unsupervised VAE and we propose a weakly-supervised method to control the pitch and formant frequencies of speech signals in the VAE latent space.'
date: 2023-02-01
venue: 'Speech Communication'
paperurl: 'https://www-sciencedirect-com.ezproxy.universite-paris-saclay.fr/science/article/pii/S0167639323000304'
citation: 'Learning and controlling the source-filter representation of speech with a variational autoencoder Samir Sadok, Simon Leglaive, Laurent Girin, Xavier Alameda-Pineda, Renaud Séguier Speech Communication, vol. 148, 2023.'
---
<p style="text-align: center;"><a href="https://samsad35.github.io/site-sfvae/">Demo</a> - <a href="https://arxiv.org/abs/2204.07075">Paper</a></p> 

Understanding and controlling latent representations in deep generative models is a challenging yet important problem for analyzing, transforming and generating various types of data. In speech processing, inspiring from the anatomical mechanisms of phonation, the source-filter model considers that speech signals are produced from a few independent and physically meaningful continuous latent factors, among which the fundamental frequency f0 and the formants are of primary importance. In this work, we show that the source-filter model of speech production naturally arises in the latent space of a variational autoencoder (VAE) trained in an unsupervised manner on a dataset of natural speech signals. Using only a few seconds of labeled speech signals generated with an artificial speech synthesizer, we experimentally illustrate that f0 and the formant frequencies are encoded in orthogonal subspaces of the VAE latent space and we develop a weakly-supervised method to accurately and independently control these speech factors of variation within the learned latent subspaces. Without requiring additional information such as text or human-labeled data, this results in a deep generative model of speech spectrograms that is conditioned on f0 and the formant frequencies, and which is applied to the transformation of speech signals.

Recommended citation: Learning and controlling the source-filter representation of speech with a variational autoencoder Samir Sadok, Simon Leglaive, Laurent Girin, Xavier Alameda-Pineda, Renaud Séguier Speech Communication, vol. 148, 2023.