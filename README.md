# Breast Cancer Classification

This project aims to classify breast cancer tumors as malignant or benign based on their features. The dataset used for this project is the <a href = "https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic">dataset</a><br/>
from the UCI Machine Learning Repository.

## Dataset

The dataset contains 569 instances of breast cancer tumors, each with 32 attributes. The attributes are:
- ID number
- Diagnosis (M = malignant, B = benign)
- Ten real-valued features are computed for each cell nucleus:
    - radius (mean of distances from center to points on the perimeter)
    - texture (standard deviation of gray-scale values)
    - perimeter
    - area
    - smoothness (local variation in radius lengths)
    - compactness (perimeter^2 / area - 1.0)
    - concavity (severity of concave portions of the contour)
    - concave points (number of concave portions of the contour)
    - symmetry 
    - fractal dimension ("coastline approximation" - 1)

The below chart shows the distribution of dataset 
<img_src="https://github.com/Farah-DeebaJ/BreastCancerClassification/blob/main/Visualisation/Distribution.png">

## Methodology

The project involves the following steps:

- Data exploration and visualization
- Data preprocessing and feature engineering
- Model selection and evaluation
- Model deployment and testing

## Results

The best model achieved an accuracy of 97.4% on the test set, using a neural network, logistic regression or k-nearest neighbors classifier. The highest accuracy on the training set was 100%, achieved by a random forest or XGBoost classifier.
