# Install
## Requirements
We test the codes in the following environments, other versions may also be compatible but Pytorch vision should be >= 1.7

- CUDA 11.3
- Python 3.7
- Pytorch 1.10.0
- Torchvison 0.11.1

## Install environment for HIPIE

```
pip3 install -e . --user
pip3 install --user shapely==1.7.1
pip3 install --user git+https://github.com/XD7479/cocoapi.git#"egg=pycocotools&subdirectory=PythonAPI"
pip3 install --user git+https://github.com/lvis-dataset/lvis-api.git
pip3 install --user jpeg4py visdom easydict scikit-image
pip3 install --user transformers tikzplotlib motmetrics

# compile Deformable Attention
cd projects/HIPIE/hipie/models/deformable_detr/ops
bash make.sh
cd ../../maskdino/pixel_decoder/ops
bash make.sh
```

## Get Pretrained Weights 
*(BERT checkpoint is necessary in model initialization)*
Language Model (BERT-base)
```
mkdir -p projects/HIPIE/bert-base-uncased
cd projects/HIPIE/bert-base-uncased
wget -c https://huggingface.co/bert-base-uncased/resolve/main/config.json
wget -c https://huggingface.co/bert-base-uncased/resolve/main/vocab.txt
wget -c https://huggingface.co/bert-base-uncased/resolve/main/pytorch_model.bin
cd ../../..
```
