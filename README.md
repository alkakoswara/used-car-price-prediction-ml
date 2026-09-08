# Used Car Price Prediction with Machine Learning

Comparative analysis of Random Forest, LightGBM, and CatBoost for used car price prediction using machine learning.

## 📌 Project Overview

This project focuses on developing and comparing machine learning models to predict the prices of used cars in Indonesia.

The study evaluates the performance of three machine learning algorithms:

- Random Forest
- LightGBM
- CatBoost

The project covers the complete machine learning workflow, from data collection and preprocessing to model development, evaluation, and deployment.

## 🎯 Objectives

- Analyze factors that influence used car prices.
- Prepare and transform used car datasets for machine learning.
- Develop predictive models using Random Forest, LightGBM, and CatBoost.
- Optimize model performance through hyperparameter tuning.
- Compare model performance using appropriate evaluation metrics.
- Deploy the selected model as a used car price prediction application.
- Integrate an LLM API to provide AI-generated insights based on prediction results.

## 🔄 Methodology

This project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology:

1. **Business Understanding** – Define the problem and prediction objectives.
2. **Data Understanding** – Collect and explore used car data.
3. **Data Preparation** – Clean, preprocess, and transform the dataset.
4. **Modeling** – Develop and tune Random Forest, LightGBM, and CatBoost models.
5. **Evaluation** – Compare model performance using R², MAE, RMSE, and 5-Fold Cross-Validation.
6. **Deployment** – Deploy the selected model with Gradio and integrate an LLM API for AI-generated insights.

## 🤖 Machine Learning Models

Three machine learning algorithms were implemented and compared:

| Model | Description |
|---|---|
| Random Forest | Ensemble learning algorithm based on multiple decision trees |
| LightGBM | Gradient boosting framework optimized for efficient training |
| CatBoost | Gradient boosting algorithm designed to handle categorical features effectively |

## 📊 Model Evaluation

The models were evaluated using:

- R² (Coefficient of Determination)
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- 5-Fold Cross-Validation

### Best Test Performance

Random Forest achieved the best performance on the unseen test dataset:

- **R²:** 0.9303
- **MAE:** Rp11.2 million

The model demonstrated strong predictive performance in estimating used car prices based on the available vehicle features.

## 🛠️ Technologies

### Programming & Data Analysis
- Python
- Pandas
- NumPy
- Scikit-learn

### Machine Learning
- Random Forest
- LightGBM
- CatBoost
- Hyperparameter Tuning
- Cross-Validation

### Data Visualization
- Matplotlib
- Seaborn
- Power BI
- Looker Studio

### Deployment & AI
- Gradio
- Large Language Model (LLM) API

## 🚀 Application

The trained model was deployed as an interactive application that allows users to enter vehicle information and receive an estimated used car price.

The application also integrates an LLM API to generate AI-powered insights based on the prediction results.

## 📁 Project Structure

```text
used-car-price-prediction-ml/
│
├── README.md
├── modeling.ipynb
├── images/
│   ├── application.png
│   └── ai-insight.png
├── deployment.ipynb

└── .gitignore
