# Painting with GANs (Generative Adversarial Networks)

---

### Introduction

In this project, we will explore how to use a Generative Adversarial Network (GAN), which is a type of unsupervised machine learning algorithm. The GAN consists of two competing neural networks: the discriminator and the generator. The discriminator tries to differentiate between real art images from a given dataset and fake images created by the generator. Meanwhile, the generator tries to create images that are so convincing that the discriminator mistakes them for real artworks. The ultimate goal is to generate new art images based on existing ones.

### What is what? 
The Discriminator uses layers to analyze and compare real and fake images, deciding if they look real or not. It does this using a type of math called a sigmoid function.

The Generator uses different layers to take random data and turn it into an image that looks real. It uses a specific kind of math called a hyperbolic tangent function for the final touches.

Both parts use a type of math called convolutional layers to process the images. It's a bit like how the brain processes information, but in this case, it's for processing images.
