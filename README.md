# Painting with GANs (Generative Adversarial Networks)

---

### Introduction

In this project, we will explore how to use a Generative Adversarial Network (GAN), which is a type of unsupervised machine learning algorithm. The GAN consists of two competing neural networks: the discriminator and the generator. The discriminator tries to differentiate between real art images from a given dataset and fake images created by the generator. Meanwhile, the generator tries to create images that are so convincing that the discriminator mistakes them for real artworks. The ultimate goal is to generate new art images based on existing ones.

### What is what? 
The Discriminator uses layers to analyze and compare real and fake images, deciding if they look real or not. It does this using a type of math called a sigmoid function.

The Generator uses different layers to take random data and turn it into an image that looks real. It uses a specific kind of math called a hyperbolic tangent function for the final touches.

Both parts use a type of math called convolutional layers to process the images. It's a bit like how the brain processes information, but in this case, it's for processing images.

---
#### Discriminator

![image](https://github.com/VaishakhiPatel/Painting_with_GAN/assets/33623183/f4f41b23-6d87-436f-97e2-85f5b0eae9e4)

#### Generator
![image](https://camo.githubusercontent.com/9405b6244799e989b74f25ba36199b203aff341ef7787522f8ee5e2a9f0a1728/68747470733a2f2f63646e2d696d616765732d312e6d656469756d2e636f6d2f6d61782f313630302f312a547637776a70425442305067367257664c6d345953412e706e67)
