# Stable Diffusion Image Generator

A Google Colab notebook that uses Hugging Face's Stable Diffusion models to generate high-quality images from text prompts.

## Overview

This project implements Stable Diffusion v1.4 in a Google Colab environment, allowing you to create detailed images based on text descriptions without requiring a powerful local GPU.

## Quick Start

1. Open the notebook in Google Colab:
   
2. Run the cells in sequence
3. Enter your text prompt to generate an image
4. Customize parameters as needed

## Features

- Text-to-image generation using Stable Diffusion
- Customizable parameters (height, width, steps, guidance scale)
- GPU acceleration through Google Colab
- Optional Streamlit integration for web interface

## How It Works

The notebook:
1. Installs necessary dependencies
2. Authenticates with Hugging Face to access models
3. Loads the required models (VAE, CLIP, UNet)
4. Sets up the diffusion process
5. Generates images based on your text prompt

## Example Prompts

Try these prompts for interesting results:

- "A digital illustration of a steampunk computer laboratory with clockwork machines, 4k, detailed, trending in artstation, fantasy vivid colors"
- "A photorealistic landscape of mountains at sunset with a lake reflection, 8k, detailed"
- "An oil painting of a cat wearing a space suit on Mars, vibrant colors, detailed"

## Requirements

The notebook automatically installs:
- transformers
- diffusers
- lpips
- accelerate
- streamlit
- pyngrok

## Tips for Better Results

- Be specific in your prompts
- Include art style references ("oil painting", "digital art", etc.)
- Mention desired quality ("detailed", "high resolution", "4k", etc.)
- Experiment with guidance scale (higher = more prompt adherence)
- Try different random seeds for variation

## License

MIT

## Acknowledgments

- [Stable Diffusion by CompVis](https://github.com/CompVis/stable-diffusion)
- [Hugging Face Diffusers](https://github.com/huggingface/diffusers)
