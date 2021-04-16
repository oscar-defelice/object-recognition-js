# Object Recognition by webcam
A  smart webcam in JavaScript with a pre-trained Machine Learning model.

---

## Introduction
This repository contains the code useful to publish a web API to take advantage of the webcam to perform object recognition. The model is a pretrained model ([coco-ssd](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)) deployed in [tensorflowjs](https://www.tensorflow.org/js/models).

### The model

This model detects objects defined in the _COCO_ dataset, which is a large-scale object detection, segmentation, and captioning dataset. You can find more information [here](http://cocodataset.org/#home). The model is capable of detecting [$80$ classes of objects](https://github.com/tensorflow/tfjs-models/blob/master/coco-ssd/src/classes.ts). (SSD stands for Single Shot MultiBox Detection).

## Usage

Simply open the [webpage](https://oscar-defelice.github.io/object-recognition-js) and enjoy!


