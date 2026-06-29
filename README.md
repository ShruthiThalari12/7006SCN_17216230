# Big Data Machine Learning using PySpark

## Module

7006SCN – Big Data Machine Learning

## Project Title

Binary Classification of NYC Yellow Taxi Payment Type Using PySpark Machine Learning

---

## Project Overview

This project applies Big Data and distributed Machine Learning techniques using PySpark to predict the payment type of New York City Yellow Taxi trips. The complete machine learning pipeline is implemented using Apache Spark and includes data ingestion, preprocessing, feature engineering, model training, evaluation, distributed computing optimisation, and Tableau dashboard visualisation.

The target variable is **payment_type**, converted into a binary classification problem:

* **1** = Credit Card Payment
* **0** = Other Payment Methods

The dataset contains over **16 million taxi trip records**, satisfying the Big Data requirements of the coursework.

---

## Dataset

**Dataset:** NYC Yellow Taxi Trip Records

Files Used:

* yellow_tripdata_2025-11.parquet
* yellow_tripdata_2025-12.parquet
* yellow_tripdata_2026-01.parquet
* yellow_tripdata_2026-02.parquet
* yellow_tripdata_2026-03.parquet
* yellow_tripdata_2026-04.parquet

Format:

* Apache Parquet

Dataset Characteristics:

* More than 16 million records
* 20 original attributes
* Open Government dataset
* Suitable for Big Data analytics

---

## Machine Learning Workflow

The project follows a complete PySpark Machine Learning pipeline consisting of:

* Data ingestion
* Data cleaning
* Missing value treatment
* Duplicate removal
* Feature engineering
* Feature scaling
* Vector assembly
* Pipeline construction
* Model training
* Hyperparameter tuning
* Cross-validation
* Model evaluation
* Performance comparison
* Tableau dashboard creation

---

## Features Used

The following ten features were selected for model development:

* passenger_count
* trip_distance
* fare_amount
* tip_amount
* total_amount
* trip_duration_minutes
* average_speed
* PULocationID
* DOLocationID
* RatecodeID

Target Variable:

* payment_type

---

## Machine Learning Models

Four classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Linear Support Vector Machine (LinearSVC)

Hyperparameter tuning was performed using:

* ParamGridBuilder
* CrossValidator
* BinaryClassificationEvaluator

---

## Evaluation Metrics

The following evaluation metrics were used:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* ROC Curve
* Precision-Recall Curve
* Feature Importance
* Model Training Time

---

## Tableau Dashboards

Four dashboards were created:

1. Data Quality & Pipeline Monitoring
2. Model Performance & Feature Importance
3. Business Insights
4. Scalability & Cost Analysis


## Repository Structure


│
├── notebooks/
│   ├── Task1.ipynb
│   ├── Task2.ipynb
│   ├── Task3.ipynb
│   ├── Task4.ipynb
│   ├── Task5.ipynb
│   └── Task6.ipynb


## Software Requirements

* Python 3.12
* Apache Spark 4.0.3
* PySpark
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* OpenPyXL
* Tableau Public





