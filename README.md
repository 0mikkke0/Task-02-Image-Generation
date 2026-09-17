# Task 02: Image Generation with Pre-trained Models

This repository contains a text-to-image generation pipeline built using the pre-trained **Stable Diffusion v1.5** model via Hugging Face `diffusers`.

## Project Overview
The model converts natural language text descriptions into detailed 512x512 digital images using latent diffusion models in PyTorch.

## Project Structure
- `task2_image_gen.py`: Script to load Stable Diffusion and generate synthetic images from text prompts.

## Requirements
```bash
pip install diffusers transformers accelerate torch
