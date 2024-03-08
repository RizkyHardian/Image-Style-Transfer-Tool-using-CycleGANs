# [Image Style Transfer Tool using CycleGANs](https://cognitiveclass.ai/courses/course-v1:IBM+GPXX0KSEEN+v1?authuser=0)

![Logo](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0KSEEN/images/starry_night.png)


You can find various implementations of CycleGANs in this [repository](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix). For this project, we will borrow a simpler implementation of CycleGANs for image style transfer. Thanks to Amy Jang, who created an easy-to-understand tutorial that goes over the basics of loading data from TFRecords, using TPUs, and building a CycleGAN for the I'm Something of a Painter Myself Kaggle competition. You can find the original tutorial [here](https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial/notebook#Create-submission-file).


Course completion of Image Style Transfer Tool using CycleGANs from CognitiveClass.ai


**Name** : Rizky Hardian Nor

**Program** : IBM Advance AI

Mentee assignment from IBM Advance AI @ Infinite Learning

## **Author** : 
 * @Roxanne Li

## Objectives

 -  Describe the novelty about CycleGANs
 -  Understand Cycle Consistency Loss
 -  Describe the complicated architecture of a CycleGAN
 -  Gain good practices of training deep learning models
 -  Implement a pre-trained CycleGAN for image style transfer

## Libraries

 - [numpy](https://numpy.org/)
 - [pillow](https://pillow.readthedocs.io/en/stable/)
 - [matplotlib](https://matplotlib.org/)
 - [keras](https://keras.io/)
 - [tensorflow](https://www.tensorflow.org/)

## Procedures

 1. Installing Required Libraries
 2. Importing Required Libraries
 3. Defining Helper Functions
 4. Loading the Dataset (dataset comes from a Kaggle competition called [I'm Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started/data))
 5. Building the Generator
 6. Building the Discriminator
 7. Building the CycleGAN Model
 8. Defining Loss Functions
 9. Training the CycleGAN model
 10. Visualize our Monet-esque photos
