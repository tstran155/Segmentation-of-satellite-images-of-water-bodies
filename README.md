# Multi-lable-classification-of-satellite-images-of-water-bodies (work in progress!)

The dataset used in this notebook is a collection of water bodies images captured by the Sentinel-2 Satellite. Each image comes with a 
black and white mask where white represents water. The masks were created to detect and measure vegetation in satellite images.

The dataset used in this work includes 2841 RGB images and 2841 black-and-white masks and can be found on Kaggle website.

https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies

The structure of this Jupyter Notebook is as follows:

1. Prepare Problem

a) Load libraries

b) Load train and test dataset

3. Prepare Data

a) Scale pixels

4. Evaluate Models

a) Define baseline CNN models

Built-in CNN model: Keras Sequential

Pre-trained CNN model: VGG16

b) Train the models

c) Make predictions and compare models

5. Improved baseline models

a) Baseline + Data Augmentation

b) Baseline + Dropout + Data Augmentation

6. Finalize Model

a) Predictions on new images (improved model)

b) Save the model for later use

7. Conclusions

