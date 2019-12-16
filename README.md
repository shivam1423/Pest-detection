# Pest_detection
Pest Detection using Deep Learning and Tensorflow from scratch.

## How to Run

Easy way: run this Colab Notebook.

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
