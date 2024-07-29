# BlossomAI
Machine Learning model to predict the species of a flower
# BlossomAI

BlossomAI is a machine learning model designed to predict the species of a flower based on its size, fragrance, and height. This project utilizes various machine learning techniques to classify different species of flowers with high accuracy.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Usage](#Usage)
- [Model Training](#model-training)
- [Conclusion](#Conclusion)


## Introduction
BlossomAI leverages machine learning algorithms to classify flower species based on input features such as size, fragrance, and height. The model is trained on a diverse dataset to ensure accuracy and reliability.

## Features
- Predict flower species based on size, fragrance, and height
- High accuracy and performance
- Easy-to-use interface
- Comprehensive dataset

## Installation
To get started with BlossomAI, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/harshr2135/BlossomAI.git


## Dataset
You can access the dataset from the below link:
https://github.com/harshr2135/BlossomAI/blob/main/flower_dataset.csv

## Usage
- Step 1: Download the notebook and csv file (save both the files preferably in the same folder).
- Step 2: Open Jupyter Notebook and navigate the the folder containing the flower_dataset.csv and blossomai.ipynb
- Step 3: Change 
         flower = pd.read_csv(os.path.join(dirname, filename)) 
         to
         flower = pd.read_csv('flower_dataset.csv'))

## Model Training
The model is trained using various machine learning algorithms. The training process involves the following steps:

-Data preprocessing
-Feature extraction
-Model selection
-Model training and evaluation

## Conclusion
* Observation - Among the 3 speices of flowers in the dataset, Rose, Hibiscus and Shoeblack Plan Hibiscus has the largest size and No Fragrance and Rose and Shoeblack Plant appear to be same in terms of size and intensity fragrance
* Prediction Model - KNeighborsClassifer car predict species of flower given its size, fragrance and height with about 90.5% accuracy whereas it drops to 81.9% when only fragrance and height is taken into consideration

