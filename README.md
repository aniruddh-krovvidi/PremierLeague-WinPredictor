# Premier League Match Predictor

This project is a machine learning-based predictor for Premier League match outcomes. It uses data scraped from [FBref](https://fbref.com/en/comps/9/Premier-League-Stats) for seasons 2020-2024 and employs scikit-learn and pandas for data analysis and prediction.

## Table of Contents

1. [Project Overview](#project-overview)
3. [Data Collection](#data-collection)
4. [Data Preprocessing](#data-preprocessing)
5. [Model Training](#model-training)
6. [How to Run](#how-to-run)

## Project Overview

The goal of this project is to predict the outcomes of Premier League matches (win or loss) using historical match data. By leveraging machine learning techniques, we aim to build a model that can accurately forecast match results based on team performance statistics.


## Data Collection

Data is collected using web scraping techniques from FBref. The scraping process is handled by BeautifulSoup and requests libraries in Python.


## Data Preprocessing

Data preprocessing is performed using pandas to clean and prepare the data for model training. This includes:

- Handling missing values
- Converting data types
- Feature engineering (e.g., calculating rolling averages for performance metrics)
- Encoding categorical variables


## Model Training

The machine learning models are trained using scikit-learn. We experiment with various classifiers to determine the best-performing model. The training process includes:

- Splitting the data into training and testing sets
- Standardizing features
- Training multiple classifiers (e.g., Logistic Regression, Random Forest, XGBoost)
- Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score


## How to Run

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook

#### This project was inspired by DataQuest


