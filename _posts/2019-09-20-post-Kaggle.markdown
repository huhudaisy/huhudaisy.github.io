---
layout:     post
title:      "Kaggle contests"
subtitle:   "One Silver medal"
date:       2019.09.05
author:     "yongwei"
header-img: "img/in-post/tag-bg.jpg"
catalog: True
tags:
    - Postgraduate
---

I participated in two kaggle competitions, one on data mining direction and one on computer vision. My kaggle's profile is as follows.
![](/img/in-post/kaggle/my_homepage.png)

## 2018 Data Science Bowl. Instance Segmentation of nuclear images. 2018

**Silver medal. Rank 39/3634. Top 2 %**

Classifying images based on their color and cell morphology. Correcting mask images and separating the connected nuclei. In order to improve the generalization of the model, it is necessary to expand the data set. Data augmentation methods such as horizontal or vertical flip data, rotation, cropping, scaling, color channel conversion, etc. are used to augment grayscale images and Neural Style Transfer is used to expand color images. The model uses the Mask-Rcnn network. In the test phase, the original images, the zoom images, and the vertical flip images are respectively predicted, and finally the results are integrated. Finally fill the small holes in the nucleus images.

The data is shown below. The picture on the right is the corresponding mask on the left
![](/img/in-post/kaggle/细胞数据.jpg)

The network structure is Mask-RCNN.
![](/img/in-post/kaggle/网络结构.jpg)

The source implementation of style migration comes from NVIDIA's "Deep Photo Style Transfer" paper. The effect is as shown on the far right of the figure.
![](/img/in-post/kaggle/风格迁移.jpg)

The left is image, the middle image is the corresponding mask, and the right image is the segmentation result. You can see that the segmentation effect is better, and there are no small holes in the cell.
![](/img/in-post/kaggle/分割结果.png)

## Safe Driver Prediction.2017

**Rank 766/5169. Top15%**

Predicting the probability that a driver will initiate a car insurance claim next year. Through data visualization to understand the data, completing feature engineering, defining multiple LightGBM models and XGBoost models as low-level models, and defining Logistics Regression as a high-order model. The output of the higher-order model is taken as the final predicted value.
