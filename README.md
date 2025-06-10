# Airfoil-Noise-Prediction-Machine-Learning-Pipeline-Using-Spark

## Project Description
This project implements a complete machine learning pipeline using Apache Spark (PySpark) to process and analyze the NASA Airfoil Self-Noise dataset. It demonstrates how to handle large-scale data, perform data cleaning, apply machine learning, evaluate the model, and persist it—all using PySpark.

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
