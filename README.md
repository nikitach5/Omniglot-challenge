# One-Shot Learning with Siamese Network
This repository tries to implement the code for Siamese Neural Networks for One-shot Image Recognition by Koch et al..

## Introduction

Siamese Networks are widely used for one shot learning tasks such as image verification and facial recognition. Siamese Nets calculate the degree of similarity or differences between given two images. The basic idea behind siamese nets is to pass two images one by one through a network and then compute the similarity score between the feature vectors produced during feedforward. In the paper, the authors have used a simple "siamese twin" convnet to compute the feature vectors. The L1 distance between the feature vectors is then passed through a fully connected layer to compute the final simmilarity score.

![siamese_model](https://user-images.githubusercontent.com/50770098/87271964-76a6e400-c4f2-11ea-93d4-9ff4f8cbc719.png)
## Code
The whole training was done on google colab. The [omniglot_p.ipynb](https://colab.research.google.com/gist/nikitach5/72e0661655b7c7fedb9f236b4acd03c2/omniglot-p.ipynb) notebook can be imported to colab for training. 

## References
- [Siamese Neural Network for One-shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)
- [One Shot Learning with Siamese Networks using Keras](https://towardsdatascience.com/one-shot-learning-with-siamese-networks-using-keras-17f34e75bb3d)
- [One Shot Learning and Siamese Networks in Keras](https://sorenbouma.github.io/blog/oneshot/)
