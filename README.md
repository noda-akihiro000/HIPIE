# Hierarchical Open-vocabulary Universal Image Segmentation
![HIPIE](assets/teaser.png)
This is the official implementation of the paper [Hierarchical Open-vocabulary Universal Image
Segmentation]

*Currently, this repo contains only codes for demos.*

## Getting started
1. Installation: Please refer to [INSTALL.md](assets/INSTALL.md) for more details..
2. Demos: 
    -  See  [Demo-Main](notebooks/Demo-Main.ipynb) for Panoptic, Part, Instance and Referring Segmentation
    -  See  [Demo-SD](notebooks/Inpaint.ipynb) for Combining our model with Stable Diffusion
    -  See  [Demo-SAM](notebooks/HIPIE+SAM.ipynb) for Combining our model with Segment Anything
## Model Zoo

We release two [checkpoints](https://drive.google.com/drive/folders/1_kD3XILU1DC8uGn4vMGHgglDVlCl1U0W?usp=sharing) at the moment.

- ResNet-50 Pretrained with O365,COCO,RefCOCO,Pascal Panoptic Parts
- ViT-H Pretrained with O365,COCO,RefCOCO

## ToDos
We will release training and evlautation code with more checkpoints soon. 