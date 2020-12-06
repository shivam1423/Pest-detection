# KWOC slack channel link
https://join.slack.com/t/pestdetection/shared_invite/zt-jrnfw1md-KT7tyKC1xUC7W7t0Co7FZQ

# Pest_detection
Pest Detection using Deep Learning and Tensorflow from scratch.

## How to Run

Easy way: run pest_detection.ipynb Colab Notebook.

To retrain the weigth you can use pest_detection_weight.ipynb Colab Notebook.

## Pest Dataset
Download Training Dataset from given Link

https://drive.google.com/file/d/1H1pf_NghWOKALC97_GpumriOSwt3xsTI/view?usp=sharing

Test Dataset is in Pest_val.zip

## Inputs

1. Convert the annotations and images from the train dataset into tfrecord.
2. Upload labelmap.pbtx file in colab.

## How to run inference on frozen TensorFlow graph
Requirements:

1. frozen_inference_graph.pb Frozen TensorFlow object detection model downloaded from Colab after training.
2. label_map.pbtxt File used to map correct name for predicted class index downloaded from Colab after training.

## To perform predictions
1. Put all the input image file in ``test/input/``.
2. Run pest_detection.ipynb Colab Notebook.
3. All the outputs images will be stored in ``test/output/``.

