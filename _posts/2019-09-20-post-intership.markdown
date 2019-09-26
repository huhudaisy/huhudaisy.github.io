---
layout:     post
title:      "	Internship. 2012 Lab of HUAWEI"
subtitle:   "Event cameras"
date:       2019.09.15
author:     "yongwei"
header-img: "img/in-post/Internship/bg.jpg"
catalog: True
tags:
    - Postgraduate
---

## Research on image reconstruction and recognition of event cameras. July. 2018 –Mar. 2019

Event cameras are inspired by biological retinal, and their working principle is different from conventional cameras. They measure intensity changes synchronously, and output event streams. Each event records the time, location and polarity of the intensity changes. Event cameras have many advantages, e.g. high dynamic range, no motion blur, low latency, high temporal resolution, low redundancy. However, frame-based image processing algorithms cannot be used directly to process event streams and it takes a lot of work to design many special algorithms. I proposed and implemented the following reconstruction algorithm.
1. Image reconstruction of event cameras based on CGAN's Event camera.
2. Image reconstruction of event cameras based on the attenuation model.

The generated images of different model. The first column shows events, and the last column shows the ground truth and other columns show the generated images. Our results are more realistic.
![](/img/in-post/Internship/result.png)
