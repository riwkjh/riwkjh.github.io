---
layout: post
title: Insects detection & classification model
subtitle: code the problem with datashift with generative model
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [image classification, object detection, GAN, data augmentation, feature engineering ]
---

 This model was part to create new vermin control system to identify vermin species and number at real time. My role was gathering datasets and train reliable models both on image classification and object detection, for over 27+ species of vermins. On the development, everything was find before things turn out that the we cannot get the images from the same source. For prediction, these images are with jpeg-compression artifactes and low-quality, different exposure and comes smaller than 1/10 to ~1/100 in resolution. To cope with this type of datasift, I tried CylclicGan along with some linear filter and generated low-quality training images from the original high-quality images. 