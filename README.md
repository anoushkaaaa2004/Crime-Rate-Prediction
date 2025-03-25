# Crime Rate Prediction using Machine Learning

## Project Overview
The **Crime Rate Prediction** project aims to predict the crime rates in different cities based on various factors such as historical crime data, crime types, and temporal aspects (time of occurrence). This project uses three different machine learning algorithms to build prediction models:
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **KMeans Clustering**

The goal of this project is to analyze the relationship between various features and crime occurrences, enabling cities to better allocate resources for law enforcement and crime prevention.

## Algorithms Used
- **K-Nearest Neighbors (KNN)**: A supervised learning algorithm used for classification tasks. The algorithm predicts the class of a data point based on the majority class of its nearest neighbors.
  
- **Random Forest**: A versatile and powerful ensemble learning method for both classification and regression. It builds multiple decision trees and merges their results to improve accuracy and control overfitting.

- **KMeans Clustering**: An unsupervised learning algorithm used for clustering data into groups. KMeans identifies inherent groupings in the data, which can be useful for segmenting areas or types of crimes based on similar features.

## Dataset Description
The dataset used in this project contains various features related to criminal activities, including:
- **Crime Type**: The type of crime that was reported (e.g., burglary, assault).
- **City**: The city where the crime occurred.
- **Date and Time**: The date and time of the crime.
- **Crime Domain**: The broader category of the crime (e.g., violent crime, property crime).
- **Crime Reported**: Whether the crime was reported or not.
- **Other features**: Additional features such as victim age, weapon used, etc.

This data helps in understanding crime patterns and predicting crime rates in different locations.

## Key Results or Findings
Through the implementation of the three algorithms, the following key insights were observed:
- **K-Nearest Neighbors (KNN)**: KNN showed good performance in predicting crime categories based on historical data, with high accuracy when the data points were well distributed.
- **Random Forest**: This model proved to be more robust and accurate in handling complex relationships between features, especially with large datasets.
- **KMeans Clustering**: KMeans helped segment cities and crime types into clusters, enabling a better understanding of high-risk areas.

The project also includes visualizations such as:
- Crime Rate by City
- Feature Distributions
- KNN Decision Boundary
- Crime Rates in Different Cities Over Time

These visualizations help to better understand the data and make predictions based on observed patterns.


