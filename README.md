# interior-design-cog
This is an implementation of the Diffusers Stable Diffusion interior design as a Cog model. Cog packages machine learning models as standard containers.

## Setup

### Download Pre-trained Weights

Before running predictions, you need to download the pre-trained weights. Use the following command to download them:

```sh
cog run script/download-weights

```

Then, you can run predictions:
```sh
cog predict -i prompt="..." -i image=@...
```
