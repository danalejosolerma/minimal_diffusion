# Minimal diffusion
In our project, we trained a deep diffusion model (DDPM) by creating a simplified version of a U-Net architecture and using various datasets. This training process allowed our DDPM to learn how to generate images from pure noise by observing a wide range of examples. By simplifying the U-Net, we made the model more efficient without losing its ability to produce good images

### Setup environment

To execute notebooks of this repository, you should install dependancies using : 

```
bash
pip install -r requirements.txt
```

### Results on MNIST

We show here a simulation of batch of images that we generated using our model using MNIST dataset.

<div align="center">
  <img src="https://github.com/danalejosolerma/minimal_diffusion/blob/main/results/gif-mnist.gif?raw=true" alt="MNIST simulation">
</div>

### Datasets



