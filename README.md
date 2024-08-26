# Industrial Copper Modeling

## Project Overview

The copper industry often deals with data that, while less complex, may suffer from issues such as skewness and noise. These issues can lead to inaccurate manual predictions, particularly in pricing and sales forecasting. This project aims to address these challenges by building machine learning models that improve the accuracy of predictions and lead classification. The solution includes regression modeling to predict the selling price and classification modeling to determine the success of leads (WON/LOST). Additionally, a Streamlit application is developed to allow users to input data and receive predictions in real time.

## Skills Takeaway

- **Python Scripting**
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Machine Learning (Regression & Classification)**
- **Feature Engineering**
- **Streamlit Web Application Development**

## Domain

- **Manufacturing**

## Problem Statement

The copper industry faces challenges in predicting pricing and classifying leads due to skewed and noisy data. Manual prediction methods are time-consuming and may not yield optimal results. This project aims to create a machine learning-based solution to predict the selling price of copper and classify leads as WON or LOST. The solution includes:

1. **Data Understanding**: Explore the dataset to identify issues like skewness and outliers.
2. **Data Preprocessing**: Clean and transform the data to make it suitable for modeling.
3. **Model Building**: Develop regression and classification models to make predictions.
4. **Streamlit Application**: Create an interactive web page to input data and display predictions.

## Data Description

The dataset includes the following columns:

1. **id**: Unique identifier for each transaction.
2. **item_date**: Date of the transaction.
3. **quantity_tons**: Quantity of copper in tons.
4. **customer**: Name or identifier of the customer.
5. **country**: Country associated with each customer.
6. **status**: Transaction status (e.g., WON, LOST).
7. **item_type**: Category of the items sold.
8. **application**: Specific use of the items.
9. **thickness**: Thickness of the items.
10. **width**: Width of the items.
11. **material_ref**: Reference or identifier for the material used.
12. **product_ref**: Reference or identifier for the specific product.
13. **delivery_date**: Expected or actual delivery date.
14. **selling_price**: Price at which the items are sold.

## Approach

### 1. Data Understanding
- Identify the types of variables (continuous, categorical).
- Explore skewness and outliers in the dataset.
- Treat reference columns as categorical variables.

### 2. Data Preprocessing
- Handle missing values with mean/median/mode.
- Treat outliers using IQR or Isolation Forest.
- Address skewness with transformations like log or Box-Cox.
- Encode categorical variables using appropriate techniques.

### 3. Exploratory Data Analysis (EDA)
- Visualize outliers and skewness before and after treatment.
- Use boxplots, distplots, and violin plots for visualization.

### 4. Feature Engineering
- Create new features and drop highly correlated ones.
- Use heatmaps to identify correlations.

### 5. Model Building and Evaluation
- Split the dataset into training and testing sets.
- Train and evaluate regression and classification models using appropriate metrics.
- Optimize model hyperparameters with techniques like cross-validation.

### 6. Streamlit Application
- Create an interactive page to input data and predict outcomes.
- Use pre-trained models to make predictions on new data.

### 7. Model Deployment
- Use the `pickle` module to save and load models (scalers, encoders, ML models).
- Develop a user-friendly interface using Streamlit.

## Tools and Libraries Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning models and preprocessing.
- **Streamlit**: Web application development.

## Learning Outcomes

- Proficiency in Python for data analysis and machine learning.
- Hands-on experience in data preprocessing, including handling missing values, outlier detection, and data normalization.
- Understanding of EDA techniques for data visualization.
- Application of machine learning models for regression and classification tasks.
- Development of a Streamlit web application to deploy machine learning models.
- Knowledge of feature engineering and model optimization.
- Insights into the challenges of the manufacturing domain and how machine learning can address them.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
