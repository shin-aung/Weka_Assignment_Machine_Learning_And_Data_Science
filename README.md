# Introductory Machine Learning and Data Science

## Overview
This repository contains assignments and practical exercises completed as part of the "Introductory Machine Learning and Data Science" course. The coursework covers various aspects of data preprocessing, supervised and unsupervised learning algorithms, and model evaluation using the Weka software. The goal of the course is to provide a foundational understanding of machine learning techniques and their applications.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Assignment 1](#assignment-1)
  - [Objectives](#objectives)
  - [Methodologies](#methodologies)
  - [Results and Insights](#results-and-insights)
- [Practicals](#practicals)
  - [Practical 1: Data Preprocessing and Initial Analysis](#practical-1-data-preprocessing-and-initial-analysis)
  - [Practical 2: Supervised Learning - Classification](#practical-2-supervised-learning---classification)
  - [Practical 3: Unsupervised Learning - Clustering](#practical-3-unsupervised-learning---clustering)
  - [Practical 4: Advanced Preprocessing Techniques](#practical-4-advanced-preprocessing-techniques)
  - [Practical 5: Ensemble Methods](#practical-5-ensemble-methods)
  - [Practical 6: Model Interpretation and Explainability](#practical-6-model-interpretation-and-explainability)
  - [Practical 7: Comparing Supervised and Unsupervised Methods](#practical-7-comparing-supervised-and-unsupervised-methods)
  - [Practical 8: Model Deployment and Evaluation](#practical-8-model-deployment-and-evaluation)
  - [Practical 9: Time Series Analysis and Forecasting](#practical-9-time-series-analysis-and-forecasting)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contact Information](#contact-information)

## Project Structure
- **Assignment_1**
  - `Assignment_1_Shin_Thant_Aung.docx`: Detailed write-up of Assignment 1.
  - `wine_train.arff`: Dataset used for the assignment.
- **Practicals**
  - **Practical_1**: Data preprocessing and initial analysis.
  - **Practical_2**: Supervised learning - classification.
  - **Practical_3**: Unsupervised learning - clustering.
  - **Practical_4**: Advanced preprocessing techniques.
  - **Practical_5**: Ensemble methods.
  - **Practical_6**: Model interpretation and explainability.
  - **Practical_7**: Comparing supervised and unsupervised methods.
  - **Practical_8**: Model deployment and evaluation.
  - **Practical_9**: Time series analysis and forecasting.

## Assignment 1

### Objectives
The primary objectives of Assignment 1 are:
- To explore the `wine_train.arff` dataset.
- To analyze the data and identify key attributes for classifying wine quality.
- To build and evaluate different machine learning models using Weka.

### Methodologies
- Data loading and visualization using Weka’s ArffViewer and Explorer.
- Descriptive statistics and histogram analysis.
- Classification model building using ZeroR, J48, and REPTree algorithms.
- Model evaluation using metrics like accuracy and confusion matrix.

### Results and Insights
- **ZeroR Algorithm**: Served as a baseline with an accuracy of 53.47%.
- **J48 Decision Tree**: Identified `alcohol` as the most informative feature for wine quality.
- **REPTree Algorithm**: Provided the best performance with a clear and interpretable model structure.

For a detailed report, refer to `Assignment_1_Shin_Thant_Aung.docx` in the `Assignment_1` directory.

## Practicals

### Practical 1: Data Preprocessing and Initial Analysis
- **Objective**: To prepare and clean the `wine_train.arff` dataset.
- **Tasks**: Handling missing values, normalization, and feature selection.
- **Outcome**: Identified key features such as `alcohol` and `volatile acidity` as significant predictors.

### Practical 2: Supervised Learning - Classification
- **Objective**: To build classification models for predicting wine quality.
- **Algorithms Used**: J48, Naive Bayes, Random Forest, Logistic Regression.
- **Results**: Random Forest achieved the highest accuracy of 82.9%.

### Practical 3: Unsupervised Learning - Clustering
- **Objective**: To identify natural groupings in the wine data.
- **Algorithms Used**: K-means, EM, Hierarchical Clustering.
- **Results**: K-means identified 3 clusters, highlighting distinct groupings based on alcohol content.

### Practical 4: Advanced Preprocessing Techniques
- **Objective**: To enhance data preprocessing with advanced techniques.
- **Techniques**: PCA for dimensionality reduction, outlier detection, feature transformation.
- **Results**: Reduced dimensionality significantly while retaining key information.

### Practical 5: Ensemble Methods
- **Objective**: To explore ensemble learning techniques.
- **Methods**: Bagging, Boosting, Stacking.
- **Results**: Boosting achieved the highest accuracy of 87.3%, effectively handling difficult cases.

### Practical 6: Model Interpretation and Explainability
- **Objective**: To interpret and explain the models built.
- **Techniques**: Decision tree analysis, feature importance metrics, visualizations.
- **Results**: Provided clear insights into feature importance and model decision processes.

### Practical 7: Comparing Supervised and Unsupervised Methods
- **Objective**: To compare the performance of different learning methods.
- **Comparison**: Supervised methods excelled in prediction tasks, while unsupervised methods revealed underlying data structures.
- **Results**: Highlighted the strengths and limitations of each approach.

### Practical 8: Model Deployment and Evaluation
- **Objective**: To deploy a selected model and evaluate its real-world performance.
- **Model Deployed**: Random Forest.
- **Evaluation**: Assessed model performance in a mock production environment, confirming robustness and reliability.

### Practical 9: Time Series Analysis and Forecasting
- **Objective**: To analyze and forecast time-dependent data using machine learning techniques.
- **Tasks**:
  - Load and preprocess a time series dataset.
  - Apply time series analysis techniques such as decomposition and differencing.
  - Build forecasting models using ARIMA, Exponential Smoothing, and others.
  - Evaluate the forecasting accuracy using metrics like RMSE and MAE.
- **Results**: 
  - Applied ARIMA to forecast future trends in the dataset, achieving a low RMSE.
  - Compared forecasting performance across different models, identifying ARIMA as the most accurate for this data.
  - Visualized the forecasting results to provide a clear understanding of future trends.

## Usage
To replicate the analysis, follow these steps:
1. Clone the repository: `git clone https://github.com/your-username/intro-machine-learning.git`
2. Navigate to the desired practical or assignment folder.
3. Open Weka and load the `.arff` dataset files.
4. Follow the steps outlined in the practical or assignment document.

## Technologies Used
- **Weka**: For data preprocessing, analysis, and model building.
- **Python**: For additional data manipulation and preprocessing (where applicable).
- **Markdown**: For documenting the repository.

## Contact Information
If you have any questions or would like to discuss this project further, feel free to reach out.

- **Name**: Shin Thant Aung
- **Email**: [shinthantstanley@gmail.com](mailto:shinthantstanley@gmail.com)
- **LinkedIn**: [linkedin.com/in/shin-thant-aung](https://www.linkedin.com/in/shin-thant-aung-882036285/)

---

Thank you for visiting my repository! If you find this project useful, please consider starring it.
