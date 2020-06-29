# TensorFlow-2.x-YOLOv3
# THIS REPO IS CUSTOMISED FROM https://github.com/pythonlessons/TensorFlow-2.x-YOLOv3

YOLOv3 implementation in TensorFlow 2.x, with support for training, transfer learning.

## Installation
First, clone or download this GitHub repository.
Install requirements and download pretrained weights:
```
pip install -r ./requirements.txt

# yolov3
wget -P model_data https://pjreddie.com/media/files/yolov3.weights

# yolov3-tiny
wget -P model_data https://pjreddie.com/media/files/yolov3-tiny.weights
```

<p align="center">
    <img width="100%" src="IMAGES/city_pred.jpg" style="max-width:100%;"></a>
</p>

## Custom Yolo v3 object detection training
Custom training required to prepare dataset first, how to prepare dataset and train custom model you can read in following link:<br>
https://pylessons.com/YOLOv3-TF2-custrom-train/
