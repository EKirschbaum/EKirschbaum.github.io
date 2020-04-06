---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  
  
&nbsp;


[DISCo: Deep learning, Instance Segmentation, and Correlations for cell segmentation in caclium imaging](https://arxiv.org/abs/1908.07957)
===

__Abstract:__ Calcium imaging is one of the most important tools in neurophysiology as it enables the observation of neuronal activity for hundreds of cells in parallel and at single-cell resolution. In order to use the data gained with calcium imaging, it is necessary to extract individual cells and their activity from the recordings. We present DISCo, a novel approach for the cell segmentation in calcium imaging videos. We use temporal information from the recordings in a computationally efficient way by computing correlations between pixels and combine it with shape-based information to identify active as well as non-active cells. We first learn to predict whether two pixels belong to the same cell; this information is summarized in an undirected, edge-weighted grid graph which we then partition. In so doing, we approximately solve the NP-hard correlation clustering problem with a recently proposed greedy algorithm. Evaluating our method on the Neurofinder public benchmark shows that DISCo outperforms all existing models trained on these datasets.

__E. Kirschbaum__, A. Bailoni, F. A. Hamrpecht: _DISCo: Deep learning, Instance Segmentation, and Correlations for cell segmentation in calcium imaging_, arXiv:1908.07957, 2019.


[LeMoNADe: Learned Motif and Neuronal Assembly Detection in calcium imaging videos](https://openreview.net/forum?id=SkloDjAqYm)
===

__TL;DR:__ We present LeMoNADe, an end-to-end learned motif detection method directly operating on calcium imaging videos.

__Abstract:__ Neuronal assemblies, loosely defined as subsets of neurons with reoccurring spatio-temporally coordinated activation patterns, or "motifs", are thought to be building blocks of neural representations and information processing. We here propose LeMoNADe, a new exploratory data analysis method that facilitates hunting for motifs in calcium imaging videos, the dominant microscopic functional imaging modality in neurophysiology. Our nonparametric method extracts motifs directly from videos, bypassing the difficult intermediate step of spike extraction. Our technique augments variational autoencoders with a discrete stochastic node, and we show in detail how a differentiable reparametrization and relaxation can be used. An evaluation on simulated data, with available ground truth, reveals excellent quantitative performance. In real video data acquired from brain slices, with no ground truth available, LeMoNADe uncovers nontrivial candidate motifs that can help generate hypotheses for more focused biological investigations.

__E. Kirschbaum__, M. Haußmann, S. Wolf, H. Sonntag, J. Schneider, S. Elzoheiry, O. Kann, D. Durstwitz, F. A. Hamprecht: _LeMoNADe: Learned Motif and Neuronal Assembly Detection in calcium imaging videos_, ICLR Proceedings, 2019.


[Sparse convolutional coding for neuronal assembly detection](https://papers.nips.cc/paper/6958-sparse-convolutional-coding-for-neuronal-assembly-detection)
===

__TL;DR:__ We present a motif detection method based on NMF which outperforms established methods in detecting motifs with temporal structure.

__Abstract:__ Cell assemblies, originally proposed by Donald Hebb (1949), are subsets of neurons firing in a temporally coordinated way that gives rise to repeated motifs supposed to underly neural representations and information processing. Although Hebb's original proposal dates back many decades, the detection of assemblies and their role in coding is still an open and current research topic, partly because simultaneous recordings from large populations of neurons became feasible only relatively recently. Most current and easy-to-apply computational techniques focus on the identification of strictly synchronously spiking neurons. In this paper we propose a new algorithm, based on sparse convolutional coding, for detecting recurrent motifs of arbitrary structure up to a given length. Testing of our algorithm on synthetically generated datasets shows that it outperforms established methods and accurately identifies the temporal structure of embedded assemblies, even when these contain overlapping neurons or when strong background noise is present. Moreover, exploratory analysis of experimental datasets from hippocampal slices and cortical neuron cultures have provided promising results.

S. Peter, __E. Kirschbaum__, M. Both, L. A. Campbell, B. K. Harvey, C. Heins, D. Durstewitz, F. Diego, F. A. Hamprecht: _Sparse convolutional coding for neuronal assembly detection_, NIPS Proceedings, 2017.
