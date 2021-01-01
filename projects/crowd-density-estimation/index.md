+++
title = "Crowd Density Estimation"
date = 2017-07-31T20:50:24-04:00
draft = false

tags = ["deep-learning", "computer-vision"]

summary = "A regression network for density estimation and head counting in a crowd"
+++
This project was done during my internship period at [the Hong Kong Applied Science and Technology Research Institute](https://www.astri.org/).

To estimate the density of a crowd and count the number of people in a public scene, I built a system which was based on the deep convolutional regression network proposed in the paper [Cross-scene crowd counting via deep convolutional neural networks](http://ieeexplore.ieee.org/document/7298684/). The system had two outputs: a floating point number indicating the estimated number of people in a scene and a 2D heat map of the crowd density in the scene.