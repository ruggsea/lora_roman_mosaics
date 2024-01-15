---
tags:
- stable-diffusion-xl
- stable-diffusion-xl-diffusers
- text-to-image
- diffusers
- lora
- template:sd-lora

base_model: stabilityai/stable-diffusion-xl-base-1.0
instance_prompt: a photo of Roman mosaic
license: openrail++
---

# SDXL LoRA DreamBooth - ruggsea/lora-trained-xl

<Gallery />

## Model description

These are the LoRA adaptation weights for stabilityai/stable-diffusion-xl-base-1.0, trained by ruggsea/lora-trained-xl.

The weights were trained using the SDXL Lora Dreambooth training script from the Diffusers library. The training parameters and other details can be found in [this](https://github.com/ruggsea/lora_roman_mosaics) repo.

LoRA for the text encoder was not enabled.

A special VAE, madebyollin/sdxl-vae-fp16-fix, was used for training.

## Trigger words

To generate images, use a photo of a Roman mosaic as the trigger.

## Download model

The weights for this model are available in Safetensors format. You can download them from the [Files & versions tab](ruggsea/lora-trained-xl/tree/main).
