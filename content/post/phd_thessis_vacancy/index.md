---
title: Ph.D thesis vacancy
date: 2020-12-01
---
<style>
body {
text-align: justify}
</style>

<strong>  Recursive learning for incomplete SAR displacement time series for Earth deformation observation </strong>

<ul>
Institutions: LISTIC, Université Savoie Mont-Blanc, L2S, Université Paris Saclay

<li> Supervisors: 
  - M. Guillaume Ginolhac, guillaume.ginolhac@univ-smb.fr (04 50 09 65 83), 
  - Mme Yajing Yan, yajing.yan@univ-smb.fr (04 50 09 65 36), 
  - M. Nabil El Korso, elkorso.nabil.mohammed@gmail.com (01 40 97 41 39) 
</li>
<li> Beginning date: October 2022 </li>

<li> Profile of candidate: The Ph.D candidate should have good skills in mathematics/statistics and/or signal/image processing. Knowledge in SAR is appreciated.</li>

<li> Keywords: SAR interferometry, robust statistics, recursive estimation, missing data imputation, time series </li>

<li> Ph.D. subject description: 

The systematic acquisition of and free access to Sentinel-1 A/B Synthetic Aperture Radar (SAR) images covering Europe every 6 days (every 12 days elsewhere) provide scientists with both opportunities and challenges for operational monitoring of Earth deformation by SAR image time series. Actually, the displacement estimation with SAR image time series has been well studied with the development of numerous multi-temporal Interferometry SAR (InSAR) methods, such as Small BAseline Subset, Permanent Scatterer Interferometry, SqueeSAR, Phase Linking methods, Multi-link InSAR, CAESAR, Least-Square estimator and EMI [1-4]. However, incremental methodological development still seems necessary in order to reply to the operational requirement, that is, the processing should be efficient and robust and the results should be reliable. 

    <ol> 
    <li> Displacement times series estimation 

Thanks to the aforementioned multi-temporal InSAR methods, the accuracy of the displacement velocity estimation has been revolutionized to millimeters per year. However, these methods are mainly retrospective analysis tools and do not allow efficient gradual integration of new SAR images that arrive over time and it is necessary to restart part of or the whole displacement estimation processing chain, which would be prohibitively expensive in practice and does not answer the need for operational monitoring. In particular, the computational cost is significant when dealing with non-Gaussian data [5] in case of high resolution SAR data. It is thus crucial to elaborate advanced recursive multi-temporal InSAR methods allowing for efficient gradual integration of new arriving SAR images. Some algorithms have already been developed in the literature, but they do not consider the non gaussianity of the data and their inherent structure [6,7]. 

In this Ph.D thesis, we aim to develop a novel robust and recursive multi-temporal InSAR approach for operational displacement estimation from SAR image time series. We consider the state-of-the-art Phase Linking approach as the baseline approach in which the sample covariance matrix of SAR image time series is fully exploited. First, we propose a sequential or recursive estimation of the covariance matrix of SAR images, taking into account the structure of the covariance matrix that is directly related to the decorrelation properties of the targets under observation. Second, we integrate temporal decorrelation models (with possible unknown parameters) providing prior information on the structure of the covariance matrix in the sequential or recursive estimation process in order to improve the efficiency. We then deploy the Expectation – Maximization (EM) algorithm to estimate jointly the unknown model parameters and the covariance matrix in an iterative way [9]. The displacement time series can be later obtained from the properly estimated covariance matrix. 

  </li>

  <li>   Missing data imputation in SAR displacement time series

Missing data can exist in the displacement time series, mainly due to the coherence loss that results in unreliable displacement estimations. Data gaps can hinder the full understanding of the phenomenon under observation. It is then necessary to fill the gaps by using some data imputation techniques [10]. 

The second objective of this Ph.D consists of imputing missing data in displacement time series, with the missing data mechanism taken into account by assuming statistical laws and estimating the parameters that describe these statistical laws. We propose to develop a new approach based on the recent reference of [11].

We consider the ''Piton de la Fournaise'' and Merapi volcano test sites as proving ground for the developed approach in this Ph.D thesis. Both descending and ascending Sentinel-1 A/B acquisitions are available. GPS measurements from permanent GNSS stations are also available for results comparison and validation.

</li>
</ol>
</li>
</ul>

 References :

<ul>
<li> [1] A. M. Guarnieri and S. Tebaldini, (2008). On the exploitation of target statistics for sar interferometry applications. IEEE Transactions on Geoscience & Remote Sensing, 46(11) :3436–3443. </li>
<li> [2] P.S. Marinkovic, F. van Leijen, G. Ketelaar, R.F. Hanssen, (2005), Recursive data processing and data volume minimization for PS-InSAR, Proceedings. 2005 IEEE International Geoscience and Remote Sensing Symposium. DOI: 10.1109/IGARSS.2005.1525622 </li>
<li> [3] S. Samiei-Esfahany, J.E. Martins, F. van Leijen, R.F. Hanssen, (2016), Phase estimation for distributed scatterers in InSAR stacks using integer least squares estimation, IEEE Transactions on Geosciences & Remote Sensing, vol.54, no.10, pp.5671-5687 </li>
<li> [4] M. Schmitt, J.L. Schönberger and U. Stilla, (2014), Adaptive covariance matrix estimation for multi-baseline InSAR data stacks, IEEE Transactions on Geosciences & Remote Sensing, 52(11), pp.6807-6817. </li>
<li> [5] H. Vu, F. Brigui, A. Breloy, Y. Yan, G. Ginolhac, A new phase linking algorithm for multi-temporal INSAR based on the maximum likelihood estimator, IGARSS 2022 </li>
<li> [6] H. Ansari, F. De Zan and R. Bamler, (2017), Sequential estimator: Towards efficient InSAR time series analysis, IEEE Transactions on Geosciences & Remote Sensing, 55(10), pp. 5637 – 5652. </li>
<li> [7] F. De Zan, (2020), Progressive InSAR phase estimation, https://arxiv.org/abs/2010.02533 </li>
<li> [8] B. Mériaux, C. Ren, M. N. El Korso, A. Breloy and P. Forster, (2019), Robust Estimation of Structured Scatter Matrices in (Mis)matched Models, Signal Processing Journal, Elsevier, vol. 165, pp.163-174. </li>
<li> [9] S. Said, H. Hajri, L. Bombrun, B. Vemuri, (2018), Gaussian Distributions on Riemannian Symmetric Spaces: Statistical Learning With Structured Covariance Matrices, IEEE Transactions on Information Theory, 64(2), pp.752-772. </li>
<li> [10] Hippert-Ferrer A., Yan Y., Bolon P., EM-EOF: gap-flling in incomplete SAR displacement time series. IEEE Transactions on Geoscience and Remote Sensing, 2020. </li>
<li> [11] Sportisse, A., Boyer, C., & Josse, J. (2020). Estimation and imputation in probabilistic principal component analysis with missing not at random data. Advances in Neural Information Processing Systems, 33, 7067-7077. </li>
</ul>
