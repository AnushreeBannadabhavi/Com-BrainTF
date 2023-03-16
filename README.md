# Com-BrainTF

Abide dataset available [here](https://drive.google.com/file/d/1rTmBuLbMNu-vW7g43eSu21ur1Sc4oVHh/view?usp=sharing).
Th

1. Update *path* in the file *source/conf/dataset/ABIDE.yaml* to the path of your dataset.

2. Run the following command to train the model.

```bash
python -m source --multirun datasz=100p model=bnt dataset=ABIDE repeat_time=5 preprocess=mixup
```

## Acknowledgement

We built Com-BrainTF on top of [BNT](https://github.com/Wayfear/BrainNetworkTransformer/tree/main)
