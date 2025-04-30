---
title: Work Package I
date: 2020-12-02
image:
  focal_point: top
---

<style>
body {
text-align: justify}
</style>


<strong> Recursive and robust displacement estimation from SAR image time series </strong>

The main objective of this work package (WP) is to develop recursive and robust multi-temporal InSAR approaches for displacement estimation from SAR image time series. The interferometric phase estimation is formulated as a covariance matrix estimation problem. This work package is based on two Ph.D. theses. In the Ph.D. thesis of Hoa Viet Phan Vu (10/2020–12/2023), we first proposed a new phase linking approach based on the Maximum Likelihood Estimator (MLE), and then extended this work to a general covariance fitting framework integrating SAR data modeling (complex circular Gaussian, generalized Gaussian), regularization (low rank, shrinkage, banding) on the covariance matrix structure and optimization algorithm (Majorization-Minimization, Riemannian gradient descent). In the Ph.D. thesis of Dana El Hajjar (12/2022– ), sequential algorithms are being developed, based on MLE-Phase Linking and covariance fitting, to efficiently integrate new images (either one by one or block by block).

  - Maximum-Likelihood-Estimator (MLE) Phase Linking
 
We start from the state-of-the-art Phase Linking approach. The N-1 phase difference is estimated directly from a time series of N coregistered SAR images based on a maximum likelihood estimator. The first contribution lies in the joint estimation of the interferometric phase and coherence, which results of superior performance in terms of the Signal-to-Noise Ratio (SNR) of wrapped interferograms compared to the state-of-the-art Phase Linking methods that require prior knowledge of the coherence. The second contribution involves the use of a more general model of scaled mixture of Gaussian to account for the non-Gaussian nature of SAR data.

  - Covariance fitting
  
  
 
  - Sequential MLE Phase Linking
 
  - Sequential covariance fitting
