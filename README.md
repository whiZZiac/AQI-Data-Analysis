# Air Quality Index (AQI) Data Analysis and Prediction

This project analyzes air quality data from cities across India (2015-2020), focusing on understanding key pollutants and predicting the Air Quality Index (AQI) using machine learning models. The primary goal is to identify trends in air pollution, highlight the impact of various pollutants, and build predictive models to forecast AQI based on historical data.

## Project Overview
This repository includes the data preprocessing, analysis, and model-building steps undertaken to analyze AQI data effectively. Various regression models were explored, with hyperparameter tuning and cross-validation used to select the best-performing model. The Random Forest model was identified as the most suitable for AQI prediction, providing strong performance metrics on unseen data.

## Key Features

### Data Preprocessing
- **Outlier and Missing Value Handling**: Outliers in pollutants such as PM2.5 and PM10 were analyzed, and missing values were imputed using K-Nearest Neighbors (KNN) imputation.
- **Feature Engineering**: Additional features like pollutant ratios and temporal variables were engineered to enhance the model’s predictive power.

### Exploratory Data Analysis
- **Visualizations**: Box plots, scatter plots, and histograms provide insights into the distribution of pollutants and their relationship with AQI.
- **Correlation Analysis**: A correlation matrix highlights the relationships among pollutants, guiding feature selection for modeling.

### Machine Learning Models
- **Regression Models**: Multiple models, including Linear Regression, k-Nearest Neighbors, Support Vector Regression, and a tuned Random Forest model, were trained and evaluated.
- **Model Evaluation**: The final model was assessed using Mean Squared Error (MSE) and R-squared (R²) to ensure accuracy and generalizability.

## Model Performance
The Random Forest model, selected after hyperparameter tuning, demonstrated strong predictive accuracy:
- **Test Set MSE**: ~0.00324
- **Test Set R²**: ~0.9502

These metrics confirm the model’s capability to generalize well to unseen data, making it a reliable tool for AQI prediction.

## Files and Structure
- **`data`**: The original dataset is available from Kaggle (see the link below). The cleaned and processed data used for analysis will be generated in this directory after running the preprocessing steps in the notebooks.
- **`notebooks`**: Jupyter notebooks for data exploration, preprocessing, and model training.
- **`plots`**: Directory for generated visualizations (e.g., box plots, scatter plots, and correlation matrices) created during the analysis.
- **README.md**: Project overview and usage instructions.

## Dataset
The dataset used in this project, "Air Quality Data in India (2015-2020)," can be downloaded from Kaggle:  
[Air Quality Data in India (2015-2020)](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

## Instructions
1. Clone this repository to your local machine.
2. Download the dataset from the provided Kaggle link and place it in the `data` directory.
3. Open the Jupyter notebooks in the `notebooks` directory to review the analysis and model training.
4. Run each notebook cell to reproduce the analysis and results.

### Usage Instructions
1. Run the notebooks in the `notebooks` folder sequentially to perform data preprocessing, analysis, and model training.
2. The visualizations will be saved in the `plots` directory after execution.

---

This README provides a concise yet informative overview of the project, guiding users through its purpose, methodology, results, and usage.

---




