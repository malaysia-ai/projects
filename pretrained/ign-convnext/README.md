# IGN-ConvNeXt

ConvNeXt Tensorflow from https://github.com/bamps53/convnext-tf

**This directory is very lack of comments, understand Tensorflow, Tensorflow estimator, Tensorflow Dataset really helpful**.

## Objective

1. Provide pretrained ConvNext image segmentation for https://github.com/koechslin/swin-transformer-semantic-segmentation dataset.

And make sure put bias on the dataset, https://github.com/koechslin/swin-transformer-semantic-segmentation#information-on-the-training

```
Dense forest => 0.5
Sparse forest => 1.31237
Moor => 1.38874
Herbaceous formation => 1.39761
Building => 1.5
Road => 1.47807
```

## Acknowledgement

Thanks to [KeyReply](https://www.keyreply.com/) for sponsoring GPU clouds to train the models.

## How-to

### EfficientNetB2

1. Run [convert-efficientnetb2-keras-to-tf1.ipynb](convert-efficientnetb2-keras-to-tf1.ipynb) to convert H5 checkpoint to Tensorflow checkpoint.

2. Run [efficientnetb2.py](efficientnetb2.py) to start pretrain.

### EfficientNetB4

1. Run [convert-efficientnetb4-keras-to-tf1.ipynb](convert-efficientnetb4-keras-to-tf1.ipynb) to convert H5 checkpoint to Tensorflow checkpoint.

2. Run [efficientnetb4.py](efficientnetb4.py) to start pretrain.

## Download
