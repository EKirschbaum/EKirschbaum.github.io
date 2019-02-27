---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  
  
&nbsp;

# [LeMoNADe: Learned Motif and Neuronal Assembly Detection in calcium imaging videos](https://openreview.net/pdf?id=SkloDjAqYm)

__TL;DR:__ We present LeMoNADe, an end-to-end learned motif detection method directly operating on calcium imaging videos.

__Abstract:__ Neuronal assemblies, loosely defined as subsets of neurons with reoccurring spatio-temporally coordinated activation patterns, or "motifs", are thought to be building blocks of neural representations and information processing. We here propose LeMoNADe, a new exploratory data analysis method that facilitates hunting for motifs in calcium imaging videos, the dominant microscopic functional imaging modality in neurophysiology. Our nonparametric method extracts motifs directly from videos, bypassing the difficult intermediate step of spike extraction. Our technique augments variational autoencoders with a discrete stochastic node, and we show in detail how a differentiable reparametrization and relaxation can be used. An evaluation on simulated data, with available ground truth, reveals excellent quantitative performance. In real video data acquired from brain slices, with no ground truth available, LeMoNADe uncovers nontrivial candidate motifs that can help generate hypotheses for more focused biological investigations.

__E. Kirschbaum__, M. Haußmann, S. Wolf, H. Sonntag, J. Schneider, S. Elzoheiry, O. Kann, D. Durstwitz, F. A. Hamprecht: _LeMoNADe: Learned Motif and Neuronal Assembly Detection in calcium imaging videos_, ICLR Proceedings, 2019.


# [Sparse convolutional coding for neuronal assembly detection](https://papers.nips.cc/paper/6958-sparse-convolutional-coding-for-neuronal-assembly-detection)

__TL;DR:__ We present a motif detection method based on NMF which outperforms established methods in detecting motifs with temporal structure.

__Abstract:__ Cell assemblies, originally proposed by Donald Hebb (1949), are subsets of neurons firing in a temporally coordinated way that gives rise to repeated motifs supposed to underly neural representations and information processing. Although Hebb's original proposal dates back many decades, the detection of assemblies and their role in coding is still an open and current research topic, partly because simultaneous recordings from large populations of neurons became feasible only relatively recently. Most current and easy-to-apply computational techniques focus on the identification of strictly synchronously spiking neurons. In this paper we propose a new algorithm, based on sparse convolutional coding, for detecting recurrent motifs of arbitrary structure up to a given length. Testing of our algorithm on synthetically generated datasets shows that it outperforms established methods and accurately identifies the temporal structure of embedded assemblies, even when these contain overlapping neurons or when strong background noise is present. Moreover, exploratory analysis of experimental datasets from hippocampal slices and cortical neuron cultures have provided promising results.

S. Peter, __E. Kirschbaum__, M. Both, L. A. Campbell, B. K. Harvey, C. Heins, D. Durstewitz, F. Diego, F. A. Hamprecht: _Sparse convolutional coding for neuronal assembly detection_, NIPS Proceedings, 2017.
