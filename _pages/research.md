---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---


{% include base_path %}

&nbsp;  

In the first part of my PhD I worked on a machine learning method that detects repeating motifs in neuronal spike matrices. These spike matrices contain discrete one-or-zero spiking events for each observed neuron. The method was based on non-negative matrix factorisation (NMF) with certain constraints that were selected such that they go along well with the nature of neuronal assemblies. The method out-performed established methods for the detection of neuronal assemblies. This method was [published at NIPS 2017](https://papers.nips.cc/paper/6958-sparse-convolutional-coding-for-neuronal-assembly-detection) and [code is available on GitHub](https://github.com/sccfnad/Sparse-convolutional-coding-for-neuronal-assembly-detection).

While presenting this method to neurobiologists inside and outside of [SFB 1134](http://sfb1134.uni-heidelberg.de), I realised that this kind of method was hardly applicable for data acquired with calcium imaging. The problem is that the calcium imaging raw data, which is a sequence of microscopy images, requires a sequence of often difficult and error-prone pre-processing steps to be converted into a spike matrix. Calcium imaging, however, is one of the most important microscopy techniques for the observation of neuronal activity. For this reason, I decided to deepen the collaboration with the calcium imaging experts within the SFB and together with them came up with a method to detect neuronal assemblies directly in calcium imaging raw data. For this I constructed a latent variable model and used a specifically designed variational autoencoder (VAE) framework in order to extract the neuronal assemblies and their activity from the data. This method was the first ever to directly detect neuronal assemblies with temporal structure in calcium imaging data and showed equivalent performance in detecting neuronal assemblies as a state-of-the-art method operating on spike matrices. The method was [published at ICLR 2019](https://openreview.net/forum?id=SkloDjAqYm) and [code is available on GitHub](https://github.com/EKirschbaum/LeMoNADe).  

Beyond the detection of neuronal assemblies there is a huge variety of interesting research questions that can be investigated using calcium imaging data. For this reason, I also worked on machine learning methods to improve the cell segmentation step in calcium imaging data and by this allow for a wider range of downstream analysis of the neuronal activity data. In this approach, the temporal context from the caclium imaging videos was used in form of pixel-wise correlations and a deep learning model was trained to predict from this input so-called pixel-wise affinities which are then used by a signed graph partitioning algorithm to gain an instance segmentation. This method was the first to combine deep learning, instance segementation and correlations for the cell segmentation in caclium imaging. The method was tested on the public [Neurofinder benchmark](http://neurofinder.codeneuro.org) and achieved great performance. The method is [published on arXiv](https://arxiv.org/abs/1908.07957) and [code is available on GitHub](https://github.com/ekirschbaum/disco). 

Originally, I started my research career in theoretical quantum chromodynamics (QCD). After attending a lecture on machine learning and intelligent systems, however, I was fascinated by machine learning and all the interesting applications it offers. Hence, I decided to focus my research on the development of machine learning algorithms for scientific applications. I got the great opportunity to do this during my PhD in the Image Analysis and Learning group of Professor Fred A. Hamprecht at Heidelberg University. 



