Car Sales Data Analysis and Price Prediction
Project Overview

This project focuses on analyzing a car sales dataset and building a machine learning model to predict car prices based on various features such as annual income, company, model, transmission type, and dealer region.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, and machine learning model development. It also provides an interactive prediction system where users can enter car details and get an estimated car price.

Dataset

The dataset contains information about car sales transactions including:

Customer information

Annual income

Car company and model

Engine type

Transmission type

Dealer details

Body style

Car price

Total records: ~23,000 rows

Project Workflow
1. Data Loading

The dataset is loaded from an Excel file using Pandas.

2. Data Cleaning

Checked for missing values

Removed null records

Removed outliers using the IQR (Interquartile Range) method

3. Exploratory Data Analysis (EDA)

Performed analysis and created visualizations such as:

Car sales over time

Company vs total sales

Dealer region vs revenue

Transmission distribution

Body style distribution

Price distribution

Correlation heatmap

Annual income vs car price relationship

Libraries used for visualization:

Matplotlib

Seaborn

4. Feature Engineering

Removed unnecessary columns

Converted categorical variables using One-Hot Encoding

5. Machine Learning Models

Two machine learning models were implemented:

Linear Regression

Random Forest Regressor

The models were trained using Scikit-learn.

6. Model Evaluation

Models were evaluated using the following metrics:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

Random Forest performed better than Linear Regression for this dataset.

7. Interactive Price Prediction

The project includes a command-line interface where users can input car details such as:

Gender

Annual Income

Company

Model

Engine type

Transmission

Color

Body Style

Dealer Region

The trained Random Forest model then predicts the estimated car price.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Machine Learning Models Used
Model	Purpose
Linear Regression	Baseline price prediction
Random Forest Regressor	Improved price prediction using ensemble learning
Project Structure
Car-Sales-Price-Prediction
│
├── CA2_project.ipynb
├── Car Sales.xlsx
├── README.md
Key Insights from the Dataset

Most popular body style: SUV

Most used transmission: Automatic

Top selling company: Chevrolet

Region with highest sales: Austin
