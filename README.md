# Autoregressive-models

# Description:
Autoregressive models are a class of generative models where the output at each step is conditioned on the previous outputs. In image generation tasks, an autoregressive model generates an image pixel by pixel, where each pixel is generated based on previously generated pixels. This approach allows models to capture intricate dependencies between pixels and generate high-quality images.

In this project, we will explore autoregressive models for image generation, specifically focusing on how they generate images sequentially.

# ✅ What It Does:
* Defines an Autoregressive model (similar to PixelCNN) that generates images by conditioning each pixel on the previously generated ones

* Trains on the CIFAR-10 dataset to generate 32x32 RGB images sequentially

* Uses MSE loss to minimize the difference between the generated images and the actual images

* The model learns the pixel dependencies and generates high-quality images from random noise
