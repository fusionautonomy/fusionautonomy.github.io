---
layout: post
title:  "ChipNet: LiDAR-based drivable region detection on an FPGA"
author: lbai
image: assets/images/project_chipnet_fig1.png
---
In this project, we proposed CNN-based a segmentation algorithm that can process LiDAR data in real-time on a single FPGA. Traditional drivable region segmentation algorithms are mostly developed on camera data, so their performance is susceptible to the light conditions and the qualities of road markings. LiDAR sensors can obtain the 3D geometry information of the vehicle surroundings with high precision. However, it is a computational challenge to process a large amount of LiDAR data in real-time. An efficient hardware architecture is proposed and implemented on an FPGA that can process each LiDAR scan in 17.59 ms, which is much faster than the previous works. Evaluated using Ford and KITTI road detection benchmarks, the proposed solution achieves both high accuracy in performance and real-time processing in speed.
![]({{site.baseurl}}/assets/images/project_chipnet_fig2.png)

