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

# Customization
Feel free to experiment with different prompts and generation parameters to explore the capabilities of the DALL-E Mini and VQ-VAE-2 models. Adjust the n_predictions variable to generate more or fewer images.

# Notes
- The code uses the DALL-E Mini and VQ-VAE-2 models for image generation. Make sure to cite the relevant papers and repositories if you use the generated images for any purpose.

- The generated images will be displayed in a 3x3 grid in the notebook.

- Ensure that you run the initialization code block before attempting to generate images.

# Acknowledgments
- DALL-E Mini: GitHub - DALL-E Mini
- VQ-VAE-2: GitHub - VQ-VAE-2 JAX
# License
This code is provided under the MIT License - see the LICENSE.md file for details.
