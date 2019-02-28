---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---


{% include base_path %}

&nbsp;  

In the first part of my PhD I worked on a method that detects repeating motifs in neuronal spike matrices. These spike matrices contain descrete one-or-zero spiking events for each observed neuron. The method was based on non-negative matrix factorisation (NMF) with certain constraints that were selected such that they go along well with the nature of neuronal assemblies. The method out-performed established methods for the detection of neuronal assemblies. This method was [published at NIPS 2017](https://papers.nips.cc/paper/6958-sparse-convolutional-coding-for-neuronal-assembly-detection) and [code is available on GitHub](https://github.com/sccfnad/Sparse-convolutional-coding-for-neuronal-assembly-detection).

While presenting this method to neurobiologists inside and outside of [SFB 1134](http://sfb1134.uni-heidelberg.de), I realised that this kind of method is almost not applicable for scientists that use calcium imaging to acquire their data. Calcium imaging, however, is one of the most important microscopy techniques for the observation of neuronal activity. The problem is that the calcium imaging raw data, which is a sequence of microscopy images, cannot be easily converted into a spike matrix. For this reason I decided to deepen the collaboration with the calcium imaging experts within the SFB and together with them came up with a method to detect neuronal assemblies directly in calcium imaging raw data. For this I constructed a latent variable model, which was based on the prior knowledge of the experts in the SFB on the nature of neuronal assemblies, and used a specifically designed variational autoencoder (VAE) framework in order to extract the neuronal assemblies and their activity from the data. This method was the first ever to directly detect neuronal assemblies with temporal structure in calcium imaging data and showed equivalent performance in detection neuronal assemblies as a method operating on spike matrices. The method was [published at ICLR 2019](https://openreview.net/forum?id=SkloDjAqYm) and [code is available on GitHub](https://github.com/EKirschbaum/LeMoNADe).  

The detection of neuronal assemblies, however, is not the only interesting task that can be performed on calcium imaging data. For this reason, I am currently working on machine learning methods to improve the cell segmentation in calcium imaging data and by this allow for a wider branch of downstream analysis of the neuronal activity data. 

