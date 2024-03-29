# Generative Adversarial Network

In this project, I aimed to implement a Generative Adversarial Network (GAN) to generate hand-written images similar to the images in the [MNIST dataset](https://www.tensorflow.org/datasets/catalog/mnist).

## Theory
Theoretical aspects of GANs, as explained in the [paper](https://arxiv.org/abs/1406.2661), are covered in the first part of the notebook. It provides an overview of how GANs work and the underlying principles behind them.

## Architecture
The network structure is divided into two main parts: the generative model and the discriminative model. These components work together to train the GAN and generate realistic hand-written images.

<div align="center">

| <img src="images/gan.png" width="400" height="200"> | 
|:--:| 
| *GAN* |
*source : [Medium](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2Fmlearning-ai%2Fgenerative-adversarial-networks-gan-introduction-and-example-3b66f5f235e9&psig=AOvVaw2DiwkBG0Jv5LZWKijswMoG&ust=1706087487049000&source=images&cd=vfe&opi=89978449&ved=0CBUQjhxqFwoTCPCH1baV84MDFQAAAAAdAAAAABAg)*
</div>

<div align="center">

| <img src="images/g.png" width="100" height="300"> | <img src="images/d.png" width="100" height="300"> |
|:--:|:--:|
| *Generator model* | *Discriminative model* |
</div>

## References
- [Generative Adversarial Networks ](https://arxiv.org/abs/1406.2661)
Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, Yoshua Bengio

