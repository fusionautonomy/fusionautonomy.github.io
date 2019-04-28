---
layout: post
title:  "Autonomous lane keeping simulator"
author: lbai
image: assets/images/project_lanekeeping_fig1.png
---
In this project, we built an autonomous lane keeping simulator with image projections of recorded data in conjunction with vehicle dynamics estimation. An end-to-end learning method using CNN takes front-view camera data as input and produces the proper steering wheel angle to keep the vehicle in lane. A novel method of data augmentation is proposed using vehicle dynamic model and vehicle trajectory tracking, which can create additional training data as if a vehicle drives off-lane in any displacement and orientation. Experimental results demonstrate that the CNN model trained with the simulator can achieve higher accuracy for autonomous lane keeping and much lower failure rate. The simulator can serve as a platform for both training and evaluation of vision based autonomous driving algorithms. 

![]({{site.baseurl}}/assets/images/project_lanekeeping_fig2.jpg)

A customized data set is built for all types of weather conditions, such as cloudy, shadowed, foggy, and sunny. Contact us if you are interested in acquiring this simulator and the dataset. 
