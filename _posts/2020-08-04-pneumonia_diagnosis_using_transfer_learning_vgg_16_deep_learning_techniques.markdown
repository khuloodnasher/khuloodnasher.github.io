---
layout: post
title:      "Pneumonia Diagnosis Using Transfer Learning VGG 16 Deep Learning Techniques"
date:       2020-08-04 14:39:12 +0000
permalink:  pneumonia_diagnosis_using_transfer_learning_vgg_16_deep_learning_techniques
---




The complete blog can be found in the url below:

https://medium.com/@khuloodnasher72/pneumonia-diagnosis-using-transfer-learning-vgg-16-deep-learning-techniques-baef845e1900



In the previous blog, I explained how you can perform pneumonia diagnosis using deep learning CNN Classification, you can read the article here.
In this blog, I would like to dive further and explain the extra deep learning state of art’s model i.e. Transfer learning using VGG 16 pre-trained model. But before I talk about VGG16, I would like to introduce the first augmentation techniques in image classification.
Augmented Model
Augmentation Techniques
In my augmented model, I tried to use Augmentation techniques to create dummy augmented data to increase the previous model accuracy as follows:
Shearing: pulling anyone off our photo and converting a square into a rhombus
Rotation: Rotating the image
Width shift: shift the image to the right or the left
Height Shift: shifting the whole image up and down
Zooming: zoom in at any particular section of our image.
Horizontal flip: mirror image along the vertical axis
Here, I defined the parameters of image transformation

