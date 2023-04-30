# Mango Leaf Disease Classification
# Introduction
This project aims to classify mango leaf diseases using deep learning techniques, specifically convolutional neural networks (CNNs), and compare their performance with traditional machine learning algorithms. Our goal is to improve disease identification and management in mango crops, which can ultimately lead to increased crop yields.

# Dataset
The dataset used in this project contains images of healthy and diseased mango leaves, with a total of eight different classes. The dataset can be found

# Dataset Details
* Train: 3200 images belonging to 8 classes
* Test: 800 images belonging to 8 classes
# Data Exploration
Images per class distribution
Average image dimensions: Width: 274.92, Height: 260.27

# Getting Started
1. Prerequisites
2. Python 3.x
3. TensorFlow 2.x
4. Keras
5. Scikit-learn
6. Matplotlib
7. Pandas

# Model
The code used in this project includes the following sections:
1. Unzipping the dataset
2. Importing required libraries
3. Defining folder names for different diseases
4. Setting dataset path and creating ImageDataGenerator for data augmentation
5. Data exploration, including counting images per class, displaying sample images, and computing average dimensions
5. Building and training the CNN model
6. Evaluating the CNN model
7. Flattening images, converting to grayscale, and splitting the dataset for traditional machine learning models
8. Training and evaluating traditional machine learning models (SVM, KNN, and Random Forest)

# Results
1. Improved CNN Model
  Test accuracy: 97.5%
2. Traditional Machine Learning Models

  * SVM: Accuracy: 0.4672, Precision: 0.4764, Recall: 0.4672, F1-score: 0.4635
  
  * KNN: Accuracy: 0.3344, Precision: 0.4100, Recall: 0.3344, F1-score: 0.3054
  
  * Random Forest: Accuracy: 0.6219, Precision: 0.6247, Recall: 0.6219, F1-score: 0.6214
  
# Contributing
We welcome contributions to this project. To contribute, please follow these steps:

1. Fork the repository
2. Create your feature branch (git checkout -b feature/your-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/your-feature)
5. Create a new Pull Request
