# Gated Convolution

## To train the model

```
First we need to create flist file for both train and test sets
```

And in training you can use random free-form mask or random rectangular mask. We have used random free-form mask. If you want use random rectangular mask you need to set MASK_TYPES: ['random_bbox'].

```
Random Rectangular Masks

RANDOM_BBOX_SHAPE: [32, 32]

RANDOM_BBOX_MARGIN: [64, 64]
```
