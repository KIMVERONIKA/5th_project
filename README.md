# 5th_project Medical X-ray Image Classification using Convolutional Neural Network
### The dataset that we are going to use for the image classification is Chest X-Ray images, which consists of 4 categories,  Covid-19, Normal, Viral Pneumonia and Bacterial Pneumonia.
### The data set is organised into 2 folders (train, test) 
### Total number of observations (images): 572
### Training observations: 532 (133 Normal cases, 133 Covid-19 cases, 133 Viral Pneumonia cases, 133 Bacterial Pneumonia cases)
### Testing observations: 40 (10 Normal cases, 10 Covid-19 cases, 10 Viral Pneumonia cases, 10 Bacterial Pneumonia cases)
# Project of Content
## 1.The Dataset
## 2.Data Analysis
## 3.Preparing the Data
### 3.1 Data Augmentation

## 4. Convolutional Neural Network
### 4.1 Fit the model
### 4.2 CNN and GridSearch

## 5. Evaluate

### Image Augmentation expands the size of the dataset by creating a modified version of the existing training set images that helps to increase dataset variation and ultimately improve the ability of the model to predict new images.
## We used to Optimize the hyperparameters of the CNN through GridSearch
###  Conclusion: 
### We’ve created a CNN model that can classify X-Ray images as Covid-19, Normal, Viral Pneumonia and Bacterial Pneumonia  with an accuracy of over 75% on the test set and 92% on the training set.
