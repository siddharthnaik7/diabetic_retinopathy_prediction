# Diabetic Retinopathy Prediction

## Abstract:
  Diabetic retinopathy remains a frightening prospect to patients and frustrates physicians. 
  Destruction of damaged retina by photocoagulation remains the primary treatment nearly 50 years after its introduction. 
  The diabetes pandemic requires new approaches to understand the pathophysiology and improve the detection, prevention, and treatment of retinopathy. 
  In this process several images from the clinics are collected and used in the deep learning model to train the images.

## Goal:
  • Predict the severity of the diabetic retinopathy prediction.
  
  • Aim is to find/build a Deep Learning (Neural Network) model that will help us classify the image in to one of the five stages of the Diabetic Retinopathy with high accuracy.

## Dataset Summary:
   The project is based on Kaggle Competition.
  
   The link for the dataset is: https://www.kaggle.com/c/aptos2019-blindness-detection/overview
  
   A clinician has rated each image for the severity of diabetic retinopathy on a scale of 0 to 4:
  
    o 0 - No DR
    
    o 1 - Mild
    
    o 2 - Moderate
    
    o 3 - Severe
    
    o 4 - Proliferative DR
    
   The dataset has following files:
  
    o train.csv - the training labels
    
    o test.csv - the test set
    
    o train.zip - the training set images
    
    o test.zip - the public test set images
    
   Total images: - 5590, Train images: - 3662
  
## Models Developed:

  o Base Model (Only CNN)
  
  o Fine Tuning with VGG16 Model
  
  o Resnet InceptionV2 Model with Oversampling
  
  o Depthwise Seperable Model
  
  o Fine Tuning with VGG19 Model
  
  o VGG19 Model with Oversampling
  
  o Densenet Model
