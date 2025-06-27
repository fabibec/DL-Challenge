# DL-Challenge

This is the final project of a Deep Learning course taught by Prof. Vincent Barra. Throughout the lecture series, we explored various deep learning models and techniques.

## Objective

The goal of this challenge was to apply the concepts covered in the course to a practical task. Specifically, we were asked to develop both a **robust classifier** and an effective **generative model**.

## Dataset

The dataset consists of grayscale images (28×28 pixels) sourced from the Google QuickDraw Dataset. It includes 5 distinct classes: **baskets**, **eyes**, **binoculars**, **rabbits**, and **hands**. Each class contains 15,000 training samples and 5,000 test samples.

## Classifier model

For classification, I designed a custom **Convolutional Neural Network (CNN)**. Its architecture and performance were evaluated through a series of systematic tests. Additionally, I compared its results against **Transfer Learning** approaches using pretrained models.

## Generative model

For the generative task, I implemented and evaluated various versions of **Variational Autoencoders (VAEs)** and **Generative Adversarial Networks (GANs)**, including conditional and non-conditional architectures.

## Sources

- [MNIST Classifier Architecture Notebook](https://www.kaggle.com/code/cdeotte/how-to-choose-cnn-architecture-mnist)
- [DCGAN Paper](https://arxiv.org/pdf/1511.06434)
- [Wasserstein GAN Paper](https://arxiv.org/pdf/1701.07875)
- Course notebooks and material provided by Prof. Barra
