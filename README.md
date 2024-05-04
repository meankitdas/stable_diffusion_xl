---
license: creativeml-openrail-m
library_name: diffusers
tags:
- stable-diffusion-xl
- stable-diffusion-xl-diffusers
- text-to-image
- diffusers
- diffusers-training
- lora
base_model: stabilityai/stable-diffusion-xl-base-1.0
inference: true
---

<!-- This model card has been generated automatically according to the information the training script had access to. You
should probably proofread and complete it, then remove this comment. -->


# LoRA text2image fine-tuning - itsankitdas/sd-dress-model-lora-sdxl

These are LoRA adaption weights for stabilityai/stable-diffusion-xl-base-1.0. The weights were fine-tuned on the Abhi5ingh/Dresscodepromptsketch dataset. You can find some example images in the following. 

![img_0](./image_0.png)
![img_1](./image_1.png)
![img_2](./image_2.png)
![img_3](./image_3.png)


LoRA for the text encoder was enabled: False.

Special VAE used for training: madebyollin/sdxl-vae-fp16-fix.


## Intended uses & limitations

#### How to use

```python
# TODO: add an example code snippet for running this diffusion pipeline
```

#### Limitations and bias

[TODO: provide examples of latent issues and potential remediations]

## Training details

[TODO: describe the data used to train the model]