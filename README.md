# DALL-E Mini and VQ-VAE-2 Image Generation

## Overview

This repository contains Python code for generating images using the DALL-E Mini and VQ-VAE-2 models. The code utilizes JAX for efficient parallel processing and image generation. The generated images are based on prompts provided to the model.

## Setup

Before running the code, make sure to install the required packages:

```bash
!pip install -q dalle-mini
!pip install -q git+https://github.com/patil-suraj/vqgan-jax.git
```
# Usage
1. Open the provided Python script in your preferred Jupyter Notebook environment.

2. Set the USE_MEGA variable to True or False to choose between DALL-E Mini models (False for smaller model, True for larger model).

3. Run the script to install the necessary packages and initialize the DALL-E Mini and VQ-VAE-2 models.

4. Configure the generation parameters:

   -  n_predictions: Number of images to generate.
   - prompt: Text prompt for image generation.
   - gen_top_k, gen_top_p, temperature, cond_scale: Generation parameters for controlling diversity and style.
     
5. Execute the code block to generate images based on the provided prompt.
