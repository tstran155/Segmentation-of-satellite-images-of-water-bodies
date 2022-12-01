# Multi-lable-classification-of-satellite-images-of-water-bodies (work in progress!)

The dataset used in this notebook is a collection of water bodies images captured by the Sentinel-2 Satellite. Each image comes with a 
black and white mask where white represents water. The masks were generated to detect and measure vegetation in satellite images.

The dataset used in this work included 2841 RGB images and 2841 black-and-white masks and can be found on Kaggle website.

https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies

The structure of this Jupyter Notebook is as follows:

Prepare Problem
a) Load libraries

b) Load dataset

Summarize Data
a) Descriptive statistics

b) Data visualizations

Prepare Data
a) Data Cleaning

b) Split-out validation dataset

c) Data Transforms

Evaluate Algorithms
a) Spot check algorithms

Machine learning: Linear Regression, Random Forest, and XGBoost

Deep learning: Keras Sequential neural network

b) Compare algorithms

Finalize Model
a) Predictions on validation dataset (best algorithm)

b) Save the model for later use

Conclusions

