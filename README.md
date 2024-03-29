# Segmentation of satellite images of water bodies

The dataset used in this notebook is a collection of water bodies images captured by the Sentinel-2 Satellite. Each image comes with a 
black and white mask where white represents water. The masks were created to detect and measure vegetation in satellite images.

The dataset used in this work includes 2841 RGB images and 2841 black-and-white masks and can be found on Kaggle website.

https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies

There are two notebooks -Keras Sequential and Pretrained Resnet50 using Pytorch- in this repository. The structure of these notebooks is as follows:

1. Prepare Problem

a) Load libraries

b) Load dataset

2. Exploratory Data Analysis

a) Image visualization

b) Image statistics

3. Prepare Data

a) Data cleaning and preprocessing (remove duplicates, blanks and abnormal size images)

b) Split data into train, test, and validation sets

4. Evaluate Models

  Notebook 1: Keras Sequential model

  Notebook 2: Pretrained ResNet50 model using Pytorch

a) Define baseline model

b) Fit model to data

5. Improved baseline models (for Notebook 1 only!)

Apply data augmentation to the images and masks

6. Finalize Model

a) Predictions on new images

b) Save the model for later use

7. Conclusions

