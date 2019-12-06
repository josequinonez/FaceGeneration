# FaceGeneration
Train a Deep Convolutional Generative Adversarial Network (DCGAN) on a dataset of celebrity faces, and generate new images

[CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

<img src='assets/processed_face_data.png' width=60% />

This is a project assignment from **Udacity Deep Learning Nanodegree program**.

The project is aimed to generate samples that should look like fairly realistic faces with small amounts of noise. The project scope spans from images loading, data preparation, and training adversarial networks. 

Most of the code and the helper functions are already provided by Udacity to focus on the network architecture that produces the best results in terms of total loss.

### Data requirements:
- Create a data folder processed_celeba_small
- Download data [by clicking here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip). This will create the images sulfolder celeba under processed_celeba_small.

### Library requirements:
- pickle
- numpy
- matplotlib
- problem_unittests
- torch
- torchvision
