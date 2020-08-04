---
layout: post
title:      "Pneumonia Diagnosis Using Deep Learning Techniques"
date:       2020-08-04 14:41:16 +0000
permalink:  pneumonia_diagnosis_using_deep_learning_techniques
---


The complete blog can be found in the url below:

https://medium.com/@khuloodnasher72/pneumonia-diagnosis-using-deep-learning-techniques-a29a64fc828b

Define the Problem
Disease diagnosis with radiology is a common practice in medicine but requires doctors to interpret the results from the x-ray images. Due to the increase in the number of patients and the low availability of doctors, there was a need for a new method to diagnose. Fortunately, machine learning has introduced the solution to this problem. In this project, we are going to introduce deep learning models and techniques in diagnosing pneumonia. Through this project, we applied deep learning CNN techniques in image classification and we followed the data science methodology as follows:


Obtain Data:
First: Preprocessing Images:
To get my data which is images here ready for classification, I performed the following preprocessing:
All the images were reshaped to size 150 by 150
Loaded image data from the hierarchical file ‘chest_xray’ using an image data generator.
Defined testing, training, validation.
Decoded the JPEG content to RGB grids of pixels.
Reshaped all images to the same size of 150 x 150 pixels
Converted pixels into floating-point tensors
Chuck data by “batch_size=32'
Rescaled the pixel values( between o and 255) to the [
