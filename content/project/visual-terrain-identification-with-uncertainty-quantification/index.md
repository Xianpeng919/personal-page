---
title: Visual Terrain Identification with Uncertainty Quantification
date: 2019-05-01T19:26:14.794Z
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
Visual information identification is one of the key problem in computer vision. Identifying various terrains using visual information is still a challenge for various  applications including smart prosthesis or smart wheelchairs. In order to ensure the security for users using smart prosthesis or wheelchairs, we want our model is able to ask for human’s help when it meets uncertainty in the real world. Thus, we use Bayesian Neural Network framework for this visual terrain identification problem..

Using a Bayesian Deep Learning framework with uncertainty quantification for visual terrain identification, we build BNN-MLP model and BNN-LSTM model. Using these two models, **we can not only identify terrains correctly, but also can measure uncertainties caused by different factors such as insufficient training data or data noise**. By comparing two models, we discover that BNN-LSTM model performs better for our visual identification problem.