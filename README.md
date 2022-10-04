# GradCAM-for-YOLOv3
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Kd4Lm6ILDO6dO0Ko6S1YGtz-KjJwvNyb?authuser=1)

**Replication of CVPR Paper - GradCAM: Visual Explanations from Deep Networks via Gradient-based Localization </br>**
Paper link is provided [here](https://openaccess.thecvf.com/content_ICCV_2017/papers/Selvaraju_Grad-CAM_Visual_Explanations_ICCV_2017_paper.pdf). </br>

This repo will provide an example of GradCAM for object detection using YOLOv3. </br>
This tutorial will use [this YOLOv3 repo](https://github.com/zzh8829/yolov3-tf2) as the reference YOLOv3 model.

## Intuition
Most tutorials on GradCAM are made for Image Classification tasks. </br>
For one of my research projects, I would like to visualize YOLOv3's Objectness Score Heatmap using GradCAM. </br>
Due to limited examples of TF 2.0 based YOLOv3 GradCAM, I decided to create my own based on [this reference](https://keras.io/examples/vision/grad_cam/). </br>
The repo is originally for image classification task, and I modified it for my applications. </br>

## Possible Updates
- [x] GradCAM for Objectness Score of YOLOv3
- [ ] GradCAM for Classification Score for Each Detected Objects by YOLOv3

Priority is given for the first task, because I needed it for my research projects. </br>
Feel free to contribute :)

## Sample images

<img src="https://github.com/yjwong1999/GradCAM-for-YOLOv3/blob/main/data/GradCAM.jpg" 
     alt="depthai" width=600><br>

## References and Acknowledgements
[GradCAM using Keras](https://keras.io/examples/vision/grad_cam/) </br>
[TF 2.0 YOLOv3](https://github.com/zzh8829/yolov3-tf2)
