# Com-BrainTF

The official Pytorch implementation of paper "Community-Aware Transformer for Autism Prediction in fMRI Connectome" accepted by **MICCAI 2023**

Abide dataset available [here](https://drive.google.com/file/d/1rTmBuLbMNu-vW7g43eSu21ur1Sc4oVHh/view?usp=sharing).

1. Update *path* in the file *source/conf/dataset/ABIDE.yaml* to the path of your dataset.

2. Run the following command to train the model.

```bash
python -m source --multirun datasz=100p model=comtf dataset=ABIDE repeat_time=5 preprocess=non_mixup
```

## Dependencies

  - python=3.9
  - cudatoolkit=11.3
  - torchvision=0.13.1
  - pytorch=1.12.1
  - torchaudio=0.12.1
  - wandb=0.13.1
  - scikit-learn=1.1.1
  - pandas=1.4.3
  - hydra-core=1.2.0

## Acknowledgement

We built Com-BrainTF on top of [BNT](https://github.com/Wayfear/BrainNetworkTransformer/tree/main)
