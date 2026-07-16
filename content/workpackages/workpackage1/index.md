---
title: Work Package I
date: 2020-12-01
---

<style>
body {
text-align: justify}
</style>

<strong> Recursive and robust displacement estimation from SAR image time series </strong>

The main objective of this work package (WP1) is to develop robust and recursive multi-temporal InSAR approaches for displacement estimation from SAR image time series. To this end, the interferometric phase estimation problem is formulated as a covariance matrix estimation problem, providing a unified framework for robust phase retrieval from stacks of SAR images. The research carried out in this work package is based on the contributions of two Ph.D. theses, which address complementary aspects of covariance modeling, interferometric phase estimation, and sequential InSAR processing.


In the Ph.D. thesis of Hoa Viet Phan Vu (10/2020–12/2023), we first proposed a novel phase-linking approach based on the Maximum Likelihood Estimator (MLE). Unlike conventional phase-linking methods, the proposed approach explicitly accounts for the non-Gaussian statistics of SAR data by modeling them with a scaled Gaussian distribution. It jointly estimates the interferometric phases and the coherence matrix within a unified estimation framework. Compared with state-of-the-art phase-linking methods, which assume Gaussian-distributed SAR data and rely on an empirical estimate of the coherence matrix, the proposed method provides more accurate and robust interferometric phase estimates, particularly in the presence of non-Gaussian scattering. We subsequently extended this work by developing a unified covariance-fitting framework that integrates SAR data modeling, covariance matrix regularization, and optimization within a common estimation strategy. The framework accommodates different statistical models for SAR data, including the complex circular Gaussian and generalized Gaussian distributions, several regularization schemes for the covariance matrix (e.g., low-rank approximation, shrinkage, and banding), and efficient optimization algorithms such as Majorization–Minimization (MM) and Riemannian gradient descent. The covariance-fitting approach estimates the interferometric phases by minimizing a dissimilarity measure between the empirical covariance matrix and its theoretical counterpart, the latter being parameterized by the unknown interferometric phases. Different objective functions can be employed, including the Kullback–Leibler divergence and the Frobenius norm (least-squares criterion). A key advantage of this framework is its flexibility. The statistical properties of SAR data can be incorporated through the construction of the empirical covariance matrix, while different decorrelation mechanisms can be modeled through appropriate regularization of the covariance matrix. This unified formulation provides a flexible and robust framework for interferometric phase estimation under a wide range of acquisition conditions.

Mains publications:

Vu P.V.H., Breloy A., Brigui F., Yan Y., Ginolhac G., Robust phase linking in InSAR, IEEE Transactions on Geosciences & Remote Sensing, 2023, vol. 61, pp. 1-11, doi :10.1109/TGRS.2023.3289338

Vu P.V.H., Breloy A., Brigui F., Yan Y., Ginolhac G., Covariance Fitting Interferometric Phase Linking : Modular Framework and Optimization Algorithms, IEEE Transactions on Geosciences & Remote Sensing, vol.63, 2025, DOI : 10.1109/TGRS.2025.3550978


In the Ph.D. thesis of Dana El Hajjar (12/2022– 12/2025), building upon our previous work on robust offline maximum-likelihood phase linking and covariance fitting methods, three sequential multi-temporal InSAR approaches have been developed to efficiently integrate newly acquired SAR images into the processing chain: Sequential Phase Linking based on Maximum Likelihood Estimation (S-MLE-PL), Sequential Covariance Fitting Interferometric Phase Linking (S-COFI-PL), and Sliding Interferometric Phase Linking (SL-IPL). The S-MLE-PL approach enables the sequential integration of individual SAR acquisitions by estimating the interferometric phase of each newly acquired image through a closed-form analytical solution derived from the conditional statistics of previously processed observations. The S-COFI-PL approach extends the covariance-fitting framework to the sequential integration of blocks of SAR images. Both S-MLE-PL and S-COFI-PL require storing the covariance matrix estimated from past acquisitions, which can become memory-intensive when processing very long SAR time series. To overcome this limitation, the SL-IPL approach enables the sequential integration of either individual SAR images or blocks of images within the covariance-fitting framework while avoiding the need to store the full historical covariance matrix. Instead, it relies on a sliding temporal window and introduces a regularization term that enforces consistency between the interferometric phase estimates in the overlapping portions of two consecutive windows. This strategy substantially reduces the memory requirements while preserving the continuity and accuracy of the estimated phase time series. Overall, these three methods enable the efficient and continuous integration of newly acquired SAR images into the displacement estimation process, while significantly reducing the computational burden associated with repeatedly processing long SAR image time series. This makes them particularly well suited for the operational monitoring of ground deformation.


Mains publications:

El Hajjar D., Ginolhac G., Yan Y., El Korso M. N., Robust sequential phase estimation using Multi-temporal SAR image series, IEEE Signal Processing Letters, 2025, vol. 32, pp.811-815, DOI : 10.1109/LSP.2025.3537334

El Hajjar D., Ginolhac G., Yan Y., El Korso M. N., Sequential Covariance Fitting for InSAR Phase Linking, IEEE Transactions on Geosciences & Remote Sensing, 2025, DOI : 10.1109/TGRS.2025.3583566

El Hajjar D., Breloy A., Ginolhac G., El Korso M. N., Yan Y., Sliding Interferometric Phase Linking for Sequential Phase Estimation in long InSAR time-series, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, under revision.

Future work will focus on extending the application of the proposed sequential multi-temporal InSAR approaches to a broader range of targets exhibiting diverse backscattering characteristics. Their performance will be further evaluated using high-resolution SAR imagery and very long time series to comprehensively assess their robustness and generalization capability. Ultimately, the objective is to integrate these methods into the national operational service, enabling their routine use for large-scale InSAR time-series processing.
