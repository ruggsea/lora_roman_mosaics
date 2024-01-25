# Lora Roman Mosaics

This repository contains code and data used to train a Lora (Low-Rank Adaptation, an efficient finetuning approach for large Diffusion models) on a dataset of Roman mosaics images. The majority of the images were sourced from the Museo Nazionale Romano - Palazzo Massimo in Rome, some of them are my own photos.

## Requirements

To use the training script, you need to clone the Diffusers library into the folder of this repository. The Diffusers library provides necessary functionality for the training process.

## Usage

1. Clone this repository to your local machine.
2. Clone the Diffusers library into the repository folder.
3. Run the training script to train the Lora model on the Roman mosaics dataset.
4. Convert the resulting Lora model to a WebUI lora using the `convert_to_webui.py` script. (A cell in the notebook is dedicated to this step, but it is not necessary to run it.)

## Result

The resulting Lora model has been converted for use in the SD WebUI by automatic1111. The file that is usable as a WebUI lora is `roman_mosaics_webui.safetensors`.

For more information, please refer to the [HuggingFace repo](https://huggingface.co/ruggsea/roman-mosaics-lora) of the Lora.
