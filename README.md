# Smartphone-Price-Detection-on-Flipkart 


# Overview
This project involves building a machine learning model to predict smartphone prices based on various features using a dataset from Flipkart. The dataset includes detailed information about smartphones available on the platform.
The goal of this project is to create a predictive model that estimates the price of smartphones based on features such as brand, color, ratings, storage capacity, and other specifications. This model can help consumers compare prices or assist sellers in setting competitive prices.

# About Dataset
The dataset used in this project includes the following columns:
* Brand: The brand of the smartphone (e.g., Samsung, Apple).
* Color_Group: The color category of the smartphone (e.g., Black, White).
* Stars: Rating of the smartphone (out of 5).
* Num_Ratings: Number of ratings the smartphone has received.
* Num_Reviews: Number of reviews the smartphone has received.
* RAM: RAM size in GB.
* Storage: Storage capacity in GB.
* Expandable: Whether the smartphone storage is expandable (Yes/No).
* Processor_Brand: Brand of the processor (e.g., Qualcomm, MediaTek).
* Display: Display specifications (e.g., 6.5 inches, AMOLED).
* Total_Cameras: Number of cameras on the smartphone.
* Battery_Capacity: Battery capacity in mAh.
* Price: Price of the smartphone (target variable).

# Tech Stack:
Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, etc


#  Objective
To predict the price of a smartphone based on the features provided in the dataset. This involves:

Exploratory Data Analysis (EDA): Understanding the dataset, removing Null values, identifying patterns, and preprocessing the data.

Feature Engineering: Transforming and encoding features(Label Encoder) to be used in the model.

Model Building: Training various machine learning models like Random Forest, KNN, Naive Bayes, Logistic Regression, SVM to predict smartphone prices.

Visualization: Creating visualizations using Matplotlib/Seaborn/Plotly to understand model performance and feature importance.

Evaluation: Assessing the model performance using metrics such as Mean Absolute Error (MAE) and R² Score, MAPE.

# Results:
Best Model: Random Forest was the best-performing model with an impressive R² score of 0.9823, showing it explains nearly all of the variance in the data. It also had the lowest Mean Absolute Error (MAE) of 914.40 and the best Mean Absolute Percentage Error (MAPE) of 0.0549.

Other models like KNN and Naive Bayes offered reasonable results but were not as accurate. Logistic Regression and Support Vector Machine were not suitable for this task due to their poor performance.
