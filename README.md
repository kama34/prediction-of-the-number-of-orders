<p align="center">
      <img src="https://i.ibb.co/0tnp8Wy/uber-eats-logo-CA3-BA2098-B-seeklogo-com.png">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Pandas-lavender" alt="Pandas">
   <img src="https://img.shields.io/badge/NumPy-thistle" alt="NumPy">
   <img src="https://img.shields.io/badge/Matplotlib-lightcyan" alt="Matplotlib">
   <img src="https://img.shields.io/badge/ydata_profiling-lavender" alt="ydata_profiling">
   <img src="https://img.shields.io/badge/Scikit_Learn-thistle" alt="Scikit-Learn">
   <img src="https://img.shields.io/badge/PCA-lightcyan" alt="PCA">
</p>

## About

Food delivery companies and systems has skyrocketed in recent years, driven by various factors. The convenience and ease of ordering food from the comfort of one’s home or office have made food delivery a preferred choice for many consumers. With a desire to optimize operational efficiency, reduce costs, and enhance customer satisfaction, food delivery companies have been leveraging machine learning algorithms to predict order cancellation and to forecast their resources such as active couriers. In this project I used machine learning to predict number of orders a courier will deliver.

## Documentation

### Introduction
This project aims to analyze courier activities and predict the total number of deliveries using machine learning techniques. The dataset contains information about couriers' mode of transportation, timestamps, and delivery statistics. Through data profiling, preprocessing, and regression modeling, the goal is to gain insights and build predictive models.

### Overview
The dataset is loaded from a JSON file and undergoes profiling to understand its structure. Categorical features, such as the mode of transportation, are processed using label encoding. Timestamp columns are transformed, and unnecessary columns are dropped. The data is split into features and targets, followed by scaling to ensure feature neutrality.

### Goals and Objectives
- Understand courier activities and patterns.
- Predict the total number of deliveries.
- Identify significant features influencing delivery counts.

### Dataset features description
* courier_id (int) : Courier ID,
* courier_transport (text) : The transport type used by a courier
* total_deliveries (int) : Total number of orders delivered by a courier
* max_unique_pickups (int) : ,
* work_start (Timestamp) : time when the courier started working
* work_finish (Timestamp) : time when the courier finished working
* late_pickups (float) : Percentage of orders that were picked up late from the vendor (during inferencing this feature gets to be the maximum acceptable late pickups)
* late_deliveries (float) : Percentage of orders that were delivered late to client (during inferencing this feature gets to be the maximum acceptable late deliveries)

### Technologies and Tools
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Mathematical operations on arrays.
- **Matplotlib**: Data visualization.
- **ydata_profiling**: Profiling the dataset to gain insights.
- **Scikit-Learn**: Machine learning library for preprocessing and modeling.
- **StandardScaler**: Scaling numerical features.
- **PCA (Principal Component Analysis)**: Dimensionality reduction technique.
- **Lasso Regression and LassoCV**: Feature selection and regularization.
- **Linear Regression and Ridge Regression**: Regression models for prediction.
- **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, **R-squared (R2)**: Evaluation metrics.

### Data Analysis
Visualizations and statistical analysis provide insights into the dataset's structure and relationships between variables with use ydata_profiling.

### Data Preparation
The dataset is loaded and profiled, and necessary preprocessing steps are taken. This includes handling categorical features, transforming timestamps, and splitting the data into features and targets.

### Feature Selection and Model Building
Lasso and LassoCV models are employed for feature selection based on their coefficients. Selected features are used to train linear regression, Lasso, and Ridge regression models. Model performance is evaluated using MAE, RMSE, and R2.

### Results Visualization
PCA is applied for dimensionality reduction, and the results are visualized using scatter plots. This provides insights into the relationships between data points.

### Machine Learning Models for Regression
Linear Regression, Lasso, and Ridge regression models are trained and evaluated on the selected features.

### Performance Evaluation
Model performance is assessed using MAE, RMSE, and R2. Results indicate the accuracy and effectiveness of each model.


## Developers

- [Kamyshnikov Dmitrii](https://github.com/kama34)

## License
