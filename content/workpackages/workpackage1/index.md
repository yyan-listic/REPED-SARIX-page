---
title: Work Package I
date: 2020-12-02
image:
  focal_point: top
---
** Recursive and robust displacement estimation from SAR image time series **

The main objective of this WP is to develop a recursive and robust multi-temporal InSAR approach for displacement estimation from SAR image time series. We start from the Phase Linking approach (based on a Maximum Likelihood estimator) proposed previsouly, namely PLML hereafter. The displacement rate is estimated directly from a time series of N coregistered SAR images based on a maximum likelihood estimator. The basic idea of this approach is to uncouple the displacement estimation problem in 2 steps : 1) estimate N-1 consistent common reference interferograms by restoring phase consistency in the interferometric stack (including N(N-1)/2 multi-reference interferograms) from the sample covariance matrix of N coregistered SAR images; 2) estimate the displacement rate from the N-1 common reference interferograms. This uncoupling can be performed based on the Extended Invariance Principle algorithm (EXIP) which allows uncoupling in 2 steps an estimation problem that would be too complicated to solve in a single step (e.g. non-convex function, non-analytical solution, etc.) or an overwhelming computational burden is required if applied to a large data set. The most important advantage of this algorithm is that it asymptotically guarantees the same optimal performance as the one-step maximum likelihood based estimator. Our efforts will be focused particularly on the first step, i.e. a robust and recursive estimation of the covariance matrix of SAR images acquired at different dates, which is essential to achieve good performance of displacement estimation. For the second step, we will follow the same approach as proposed in the PLML approach. 

Task I: robust multi-temporal InSAR

Task II: recursive multi-temporal InSAR 

Task III: Missing data imputation
