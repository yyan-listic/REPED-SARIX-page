---
title: Work Package II
date: 2020-12-01
---

<style>
body {
text-align: justify}
</style>

<strong> Geophysical inverse modeling by neural networks </strong>

Surface displacement fields constitute one of the major sources to explore the subsurface feature of the Earth by means of inversion. The latter involves modeling the deformation source and physical mechanism at depth that explain the displacement fields observed at the Earth’s surface. Solving such an inverse problem means finding a set of model parameters that best fit the observations. The state-of-the-art approaches, e.g. Markov Chain Monte Carlo (MCMC), require overwhelming amount of computing resources and prior knowledge about the model parameters to retrieve. The recent advent of neural networks based machine learning paradigms enables the development of new solutions to tackle the previous shortcomings of knowledge-driven inversions.

In this Work Package (WP2), we address the major challenges of neural network-based inversion and prediction from SAR displacement time series. The objective is to develop a supervised deep-learning framework capable of estimating key geophysical parameters that are strongly related to natural hazards but cannot be directly observed, such as the overpressure within a magma chamber. The research carried out in this work package is based on the contributions of the M2 internship and the Ph.D. thesis of Lorenzo Lopez-Uroz (01/10/2022 - abandon in 02/2025). A proof-of-concept study was first conducted to investigate the potential of neural networks for geophysical inverse modeling, with the objective of estimating glacier ice thickness in the Swiss Alps from surface flow velocity measurements and a digital elevation model. Using a ResNet architecture trained on a limited dataset combining surface velocity measurements and ice thickness estimates derived from Ground Penetrating Radar (GPR) observations, the proposed approach efficiently estimated the ice thickness of approximately 1,400 glaciers with diverse characteristics (e.g., size, slope, and orientation) through a single inference process. This demonstrates a major advantage of neural networks over traditional physics-based inversion approaches, which generally require individual modeling and optimization procedures for each glacier. However, the predictive accuracy of the neural network approach remains lower than that achieved by physics-based inversion methods in some cases, with a systematic underestimation of ice thickness observed. Based on expert knowledge, glacier hypsometry provides valuable physical information: for glaciers in equilibrium, the maximum ice thickness is generally located near the equilibrium line altitude, which can be inferred from the altitude–area distribution curve. To incorporate this prior knowledge and improve the predictive capability of the neural network, hypsometric information was introduced as an additional input feature. Although the underestimation issue has not been fully resolved, the integration of hypsometry reduced the variability of predictions obtained from different training runs initialized with random weights. As a proof of concept, this study demonstrates the potential of neural networks for efficient geophysical inverse modeling and highlights the importance of incorporating physical knowledge to improve their reliability and robustness.


This work was further extended to a similar inverse problem in volcanology, namely the estimation of the depth and volume change of a Mogi-type magmatic source from InSAR-derived surface displacement fields. Due to the limited availability of real observations, synthetic displacement fields generated using the Mogi model were used to train the ResNet model. Although a slight underestimation of the estimated parameters was observed, the comparison with a Markov Chain Monte Carlo (MCMC)-based inversion approach demonstrated the validity of the ResNet predictions. Further investigations showed that introducing varying levels of noise into the simulated displacement measurements during training improves the generalization capability of the model. In addition, fine-tuning was found to be beneficial when applying a globally trained model to individual volcanoes with specific characteristics. Finally, the application of the proposed approach to real InSAR displacement data over volcanoes in the Kenya Rift region further confirmed the predictive capability of the ResNet model. 


In summary, the potential of deep learning approaches for inverse modeling problems in glaciology and volcanology has been demonstrated. Compared with traditional Bayesian approaches based on physical models, the proposed ResNet-based framework achieves a significant reduction in computational cost, highlighting its potential for efficient parameter estimation from displacement time series. However, further improvements are still required to enhance the accuracy and generalization capability of the ResNet model.

Main publications:

Lopez-Uroz L., Yan Y., Benoit A., Albino F., Bouygues P., Giffard-Roisin S., Pinel V., Exploring Deep Learning for Volcanic Source Inversion, IEEE Transactions on Geosciences & Remote Sensing, 2024, vol. 62, doi :10.1109/TGRS.2024.3494253.

opez-Uroz L., Yan Y., Benoit A., Rabatel A., Giffard-Roisin S., Lin-Kwong-Chon C., Using Deep Learning for Glacier Thickness Estimation at a Regional Scale, IEEE Geosciences & Remote Sensing Letters, 2024, vol. 21, pp.1-5, doi : 10.1109/LGRS.2024.3353575



Future research will focus on improving the accuracy and generalization capability of the proposed ResNet-based model. Particular attention will be given to the integration of physical knowledge into the neural network architecture in order to develop physics-informed learning strategies. In addition, alternative deep learning architectures, such as autoencoders, will be investigated to jointly estimate the physical parameters and reconstruct the associated displacement fields, thereby providing a more consistent and physically meaningful inversion framework.


