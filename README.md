# Final Project Big Data - Classification Other Algorithms

### Apache Spark with logistic regression Algorithm

- Name: Kurnia Cahya Febryanto
- Student ID: 5025201073
- Class: Big Data A

### Algorithm:
- Logistic Regression Algorithm with Apache Spark

### Dataset:
Link Dataset: [Hotel Reservation Dataset](https://www.kaggle.com/ahsan81/hotel-reservations-classification-dataset)

### Description of the Dataset
The `Hotel Reservations Classification Dataset` provides data pertaining to hotel reservations, which includes a variety of factors such as booking changes, deposit type, days in waiting list, and other customer details. 

With the advent of online hotel reservation channels, booking behaviors of customers have significantly evolved. However, a substantial number of these reservations get cancelled or result in no-shows due to various reasons like change of plans or scheduling conflicts. While the option to cancel free of charge or at a low cost is advantageous for hotel guests, it often results in potential revenue loss for hotels.

Therefore, the objective of this project is to use this dataset to build a machine learning model that can predict whether a hotel booking will be cancelled or not. This information can potentially help hotels in better managing their resources and maximizing their revenues.

### Table of Contents
1. [Dataset Description](#dataset-description)
   - [Source of the Dataset](#source-of-the-dataset)
   - [Description of the Dataset](#description-of-the-dataset)
2. [Data Acquisition](#data-acquisition)
   - [Setting Up Kaggle API](#setting-up-kaggle-api)
   - [Downloading Dataset](#downloading-dataset)
3. [Setting Up the Environment](#setting-up-the-environment)
   - [Installation of Dependencies](#installation-of-dependencies)
   - [Setting Up Apache Spark](#setting-up-apache-spark)
4. [Data Loading and Exploration](#data-loading-and-exploration)
   - [Loading Dataset into Spark DataFrame](#loading-dataset-into-spark-dataframe)
   - [Initial Data Exploration](#initial-data-exploration)
5. [Data Preprocessing](#data-preprocessing)
   - [Handling Missing Values](#handling-missing-values)
   - [Feature Scaling/Normalization](#feature-scalingnormalization)
6. [Feature Engineering](#feature-engineering)
   - [Feature Selection](#feature-selection)
   - [Feature Preparation](#feature-preparation)
7. [Model Building](#model-building)
   - [Choice of Classification Algorithm](#choice-of-classification-algorithm)
   - [Reason for Choosing the Algorithm](#reason-for-choosing-the-algorithm)
8. [Parameter Tuning](#parameter-tuning)
   - [Initial Model Training](#initial-model-training)
   - [Hyperparameter Tuning](#hyperparameter-tuning)
   - [Retraining Model with Optimized Parameters](#retraining-model-with-optimized-parameters)
9. [Model Evaluation](#model-evaluation)
   - [Accuracy](#accuracy)
   - [Confusion Matrix](#confusion-matrix)
   - [Precision, Recall, and F1 Score](#precision-recall-f1-score)
10. [Visualization](#visualization)
    - [Data Visualization during Preprocessing](#data-visualization-during-preprocessing)
    - [Data Visualization during Evaluation](#data-visualization-during-evaluation)
11. [Conclusion](#conclusion)
12. [References](#references)