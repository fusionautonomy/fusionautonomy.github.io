---
layout: post
title:  "Understanding traffic scene via segmentation and object detection"
author: lbai
image: assets/images/project_yolofcn_fig1.jpg
---
We developed a deep learning based self-driving perception system which can detect moving objects and perform semantic segmentation for static surroundings simultaneously. We integrate object detection and semantic segmentation models together. We choose FCN for semantic segmentation and YOLO for object detection which can meet the real time requirement by handling images 30FPS. We also re-design the lost function for YOLO to make it focus on small object better for remote car. We test our idea on popular multi-task traffic dataset KITTI. Varies experiments results show our model can improve the object detection accuracy and model converge speed with the exact complexity as original FCN model and YOLO model.


