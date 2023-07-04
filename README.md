# HIPIE: Hierarchical Open-vocabulary Universal Image Segmentation

We present **HIPIE**, a novel HIerarchical, oPen-vocabulary and unIvErsal image segmentation and detection model that is capable of performing segmentation tasks at various levels of granularities (whole, part and subpart) and tasks, including semantic segmentation, instance segmentation, panoptic segmentation, referring segmentation, and part segmentation, all within a unified framework of language-guided segmentation. 

<p align="center"> <img src='assets/teaser.png' align="center" > </p>            

> [**Hierarchical Open-vocabulary Universal Image Segmentation**](http://people.eecs.berkeley.edu/~xdwang/projects/HIPIE/)            
> [Xudong Wang*](https://people.eecs.berkeley.edu/~xdwang/), [Shufan Li*](https://homepage.jackli.org/), [Konstantinos Kallidromitis*](https://tech-ai.panasonic.com/en/researcher_introduction/048/), Yusuke Kato, Kazuki Kozuka, [Trevor Darrell](https://people.eecs.berkeley.edu/~trevor/)            
> Berkeley AI Research, UC Berkeley; Panasonic AI Research            

[[`project page`](http://people.eecs.berkeley.edu/~xdwang/projects/HIPIE/)] [[`arxiv`](https://arxiv.org/abs/2307.00764)] [[`paper`](https://arxiv.org/pdf/2307.00764.pdf)] [[`bibtex`](#citation)]

*Currently, this repo contains only codes for demos. Stay tuned.*  


## Installation
Please refer to [INSTALL.md](assets/INSTALL.md) for more details.  


## Demos
-  See  [Demo-Main](notebooks/Demo-Main.ipynb) for Panoptic, Part, Instance and Referring Segmentation
-  See  [Demo-SD](notebooks/Inpaint.ipynb) for Combining our model with Stable Diffusion
-  See  [Demo-SAM](notebooks/Demo-HIPIE+SAM.ipynb) for Combining our model with Segment Anything

<p align="center">
  <img src="assets/HIPIE-SAM-demos.gif" width=100%>
</p>
HIPIE is also capable of labeling segmentation masks from SAM and can even identify additional masks that may have been overlooked by SAM.

Please check our [project page](http://people.eecs.berkeley.edu/~xdwang/projects/HIPIE/) for more demos!

## Model Zoo
We release two [checkpoints](https://drive.google.com/drive/folders/1_kD3XILU1DC8uGn4vMGHgglDVlCl1U0W?usp=sharing) at the moment.

- ResNet-50 Pretrained with O365,COCO,RefCOCO,Pascal Panoptic Parts
- ViT-H Pretrained with O365,COCO,RefCOCO


## ToDos
We will release training and evlautation code with more checkpoints soon. 


## License
The majority of HIPIE is licensed under the [MIT license](LICENSE). If you later add other third party code, please keep this license info updated, and please let us know if that component is licensed under something other than CC-BY-NC, MIT, or CC0.


## How to get support from us?
If you have any general questions, feel free to email us at [Xudong Wang](mailto:xdwang@eecs.berkeley.edu), [Shufan Li](mailto:jacklishufan@berkeley.edu) and [Konstantinos Kallidromitis](mailto:kk984@cornell.edu). If you have code or implementation-related questions, please feel free to send emails to us or open an issue in this codebase (We recommend that you open an issue in this codebase, because your questions may help others). 


## Citation
If you find our work inspiring or use our codebase in your research, please consider giving a star ⭐ and a citation.
```
@misc{wang2023hierarchical,
  title={Hierarchical Open-vocabulary Universal Image Segmentation}, 
  author={Xudong Wang and Shufan Li and Konstantinos Kallidromitis and Yusuke Kato and Kazuki Kozuka and Trevor Darrell},
  year={2023},
  eprint={2307.00764},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```
