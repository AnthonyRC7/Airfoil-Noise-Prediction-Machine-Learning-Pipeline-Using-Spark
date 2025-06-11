# Airfoil-Noise-Prediction-Machine-Learning-Pipeline-Using-Spark

## Problem Statement
Aerodynamic design requires precise modeling to optimize airfoil efficiency for planes and sports cars. However, data scientists face challenges due to heterogeneous data formats and the complexity of integrating machine learning workflows into the engineering process. Without a streamlined data pipeline, extracting meaningful insights for airfoil noise prediction becomes inefficient, limiting innovation in aerodynamic design.

## Goal
This project aims to clean, process, and unify airfoil noise data by developing an ETL pipeline that prepares structured datasets for machine learning. Using the modified NASA Airfoil Self Noise dataset, the pipeline will handle data cleaning, feature engineering, and model training to predict SoundLevel based on aerodynamic parameters. The final ML model will be evaluated and persisted, enabling accurate noise predictions to enhance airfoil design efficiency.

## Objectives

### Part 1: Perform ETL Activities
- Load the airfoil dataset from a CSV file
- Remove duplicate rows
- Drop rows containing null values
- Perform necessary data transformations
- Save the cleaned dataset in **Parquet** format

### Part 2: Create a Machine Learning Pipeline
- Split the data into training and testing sets
- Build a PySpark ML pipeline
- Train a regression model to predict **SoundLevel**

### Part 3: Evaluate the Model
- Evaluate model performance using:
  - Root Mean Squared Error (RMSE)
  - R² Score

### Part 4: Persist the Model
- Save the trained model to disk
- Load the model and verify that it performs as expected

---

## 🛠️ Technologies Used

- **Apache Spark (PySpark)** – for scalable data processing and ML
- **Spark MLlib** – for machine learning pipelines and model evaluation
- **Parquet** – for efficient columnar data storage
- **Python 3.x**

---
