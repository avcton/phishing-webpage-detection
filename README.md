
# Phishing Webpages Detection

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Explainable AI](#explainable-ai)
- [Results](#results)
- [Contributors](#contributors)

## Project Overview
This project focuses on detecting phishing websites using various machine learning models. The primary objective is to preprocess the dataset, select the best features, and identify the most effective models for accurate classification. Phishing websites pose a significant threat to users, and effective detection mechanisms can help mitigate these risks.

## Dataset
The dataset used in this project is `web-page-phishing.csv`. It contains features related to web page characteristics, such as URL length, number of special characters, and other indicators that help determine whether a site is a phishing site or not.

## Dependencies
The project requires several Python libraries to function correctly, including:
- numpy
- pandas
- seaborn
- matplotlib
- tensorflow
- scikit-learn
- imbalanced-learn
- scikeras
- lime
- shap

## Installation
To set up the project, follow these steps:
1. Clone the repository from GitHub.
2. Navigate to the project directory.
3. Install the required dependencies.

## Usage
1. Clone the repository and navigate to the project directory.
2. Open the Jupyter notebook file `DM_Final_Project.ipynb`.
3. Run the cells sequentially to execute the project steps.

## Preprocessing
The preprocessing steps include:
- **Handling Null Values:** Checking and addressing any missing data in the dataset.
- **Standardization:** Scaling the features to ensure they have a mean of 0 and a standard deviation of 1.
- **Determining Multicollinearity:** Using a correlation matrix to identify and address highly correlated features.

## Modeling
The project involves training and evaluating multiple machine learning models, including:
- XG Boost
- Random Forest
- Decision Trees
- Gradient Boosting
- K-Nearest Neighbors (KNN)
- MLP Classification
- Neural Networks
- Deep Neural Networks

From the initial 12 proposed models, the best 8 models were selected based on their performance metrics for further evaluation and optimization.

## Explainable AI 
To understand the decisions made by the machine learning models, we utilize explainable AI techniques. These techniques help to interpret and explain the model predictions, ensuring transparency and trust in the model's decisions. In this project, we use the following methods: 
- **LIME (Local Interpretable Model-agnostic Explanations):** This technique explains individual predictions by approximating the model locally with an interpretable model. 
- **SHAP (SHapley Additive exPlanations):** This method provides consistent and locally accurate feature attribution values for each prediction.

## Results
The results section includes:
- Performance metrics for each model (e.g., accuracy, precision, recall, F1-score).
- Visualizations such as confusion matrices and ROC curves.
- Insights and interpretations of the model performances.

## Contributors
- [Muhammad Abdullah](https://github.com/Mabdullahatif)
- Farheen Akmal

