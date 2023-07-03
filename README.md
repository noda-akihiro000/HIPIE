# Hierarchical Open-vocabulary Universal Image Segmentation

**HIPIE** can provide high-quality class-aware image segmentation for a wide range of objects/parts. We consider all relevant tasks under the unified framework of language-guided segmentation, which performs open-vocabulary segmentation and detection tasks for arbitrary text-based descriptions.

<p align="center"> <img src='assets/teaser.png' align="center" > </p>            

> [**Hierarchical Open-vocabulary Universal Image Segmentation**](http://people.eecs.berkeley.edu/~xdwang/projects/HIPIE/)            
> [Xudong Wang*](https://people.eecs.berkeley.edu/~xdwang/), [Shufan Li*](https://rohitgirdhar.github.io/), Konstantinos Kallidromitis*, Yusuke Kato, Kazuki Kozuka, [Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/)            
> Berkeley AI Research, UC Berkeley; Panasonic AI Research            

[project page](http://people.eecs.berkeley.edu/~xdwang/projects/HIPIE/) | [arxiv]() | [demo]() | [bibtex](#citation)

*Currently, this repo contains only codes for demos. Stay tuned.*  


## Installation
Please refer to [INSTALL.md](assets/INSTALL.md) for more details.  


## Demos
-  See  [Demo-Main](notebooks/Demo-Main.ipynb) for Panoptic, Part, Instance and Referring Segmentation
-  See  [Demo-SD](notebooks/Inpaint.ipynb) for Combining our model with Stable Diffusion
-  See  [Demo-SAM](notebooks/Demo-HIPIE+SAM.ipynb) for Combining our model with Segment Anything


## Model Zoo
We release two [checkpoints](https://drive.google.com/drive/folders/1_kD3XILU1DC8uGn4vMGHgglDVlCl1U0W?usp=sharing) at the moment.

- ResNet-50 Pretrained with O365,COCO,RefCOCO,Pascal Panoptic Parts
- ViT-H Pretrained with O365,COCO,RefCOCO


## ToDos
We will release training and evlautation code with more checkpoints soon. 


## License
HIPIE is licensed under the [MIT license](LICENSE). If you later add other third party code, please keep this license info updated, and please let us know if that component is licensed under something other than CC-BY-NC, MIT, or CC0.


## How to get support from us?
If you have any general questions, feel free to email us at [Xudong Wang](mailto:xdwang@eecs.berkeley.edu), [Shufan Li](mailto:jacklishufan@berkeley.edu) and [Konstantinos Kallidromitis](mailto:kk984@cornell.edu). If you have code or implementation-related questions, please feel free to send emails to us or open an issue in this codebase (We recommend that you open an issue in this codebase, because your questions may help others). 


## Citation
If you find our work inspiring or use our codebase in your research, please consider giving a star ⭐ and a citation.
```
@inproceedings{wang2023Hierarchical,
  title={Hierarchical Open-vocabulary Universal Image Segmentation},
  author={Wang, Xudong and Li, Shufan and Kallidromitis, Konstantinos and Kato, Yusuke and Kozuka, Kazuki and Darrell, Trevor},
  journal={arXiv preprint arXiv:xxxxx.xxxx},
  year={2023}
}
```