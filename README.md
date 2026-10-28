# Healthcare & Lifestyle Analytics — BRFSS 2023

An end-to-end data analysis and machine learning project using the **2023 Behavioral Risk Factor Surveillance System (BRFSS)** dataset published by the U.S. Centers for Disease Control and Prevention (CDC).

The project explores health and lifestyle patterns through data cleaning, exploratory data analysis, visualizations, classification, regression, and feature importance analysis.

## Project Overview

The objective of this project is to explore how health-related and lifestyle factors are associated with diagnosed diabetes and reported sleep duration.

The notebook uses Python libraries for data processing, visualization, and machine learning to analyze selected variables from the BRFSS 2023 survey.

## Objectives

- Explore and understand the BRFSS 2023 dataset.
- Clean survey response codes and prepare selected health and lifestyle variables.
- Perform exploratory data analysis (EDA).
- Visualize distributions, missing values, correlations, and subgroup patterns.
- Build machine learning models to classify diagnosed diabetes status.
- Compare regression models for predicting reported sleep duration.
- Examine feature importance and demonstrate example predictions.

## Dataset

**Dataset:** Behavioral Risk Factor Surveillance System (BRFSS), 2023

**Source:** U.S. Centers for Disease Control and Prevention (CDC)

Official dataset page:  
https://www.cdc.gov/brfss/annual_data/annual_2023.html

The dataset contains survey information about health status, chronic conditions, physical activity, demographics, and other health-related behaviors.

The notebook downloads the compressed SAS Transport dataset and prepares selected variables for analysis.

## Technologies Used

- **Python** — programming language
- **Pandas** — data manipulation and analysis
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Scikit-learn** — machine learning and model evaluation
- **Pyreadstat** — statistical data file support
- **Jupyter Notebook / Google Colab** — development environment

## Project Workflow

### 1. Data Collection
Download the official BRFSS 2023 dataset from the CDC.

### 2. Data Understanding
Inspect dataset dimensions, column names, data types, and missing values.

### 3. Data Cleaning and Preparation
Select relevant health and lifestyle variables, handle special survey response codes, create readable labels, and prepare analysis-ready features.

### 4. Exploratory Data Analysis
Analyze missing values, numerical distributions, diabetes prevalence, and relationships between health and lifestyle indicators.

### 5. Data Visualization
Generate histograms, bar charts, and correlation heatmaps to explore patterns in the data.

### 6. Diabetes Classification
Train and compare classification models to predict diagnosed diabetes status using selected demographic, health, and lifestyle features.

### 7. Sleep Duration Regression
Compare regression models to estimate reported sleep duration from selected features.

### 8. Feature Importance
Use permutation importance to identify features that influence the selected classification model's predictions.

### 9. Example Predictions and Results
Demonstrate predictions and export cleaned analysis data and model comparison results to CSV files.

## Machine Learning Tasks

**Classification:** Predict diagnosed diabetes status.

Models include Logistic Regression, Decision Tree, Random Forest, and other tree-based or ensemble classifiers defined in the notebook.

**Regression:** Predict reported sleep duration.

Models include Ridge Regression, Decision Tree Regressor, Random Forest Regressor, and Extra Trees Regressor.

The notebook compares model performance using classification metrics such as accuracy, precision, recall, and F1-score, and regression metrics such as MAE and RMSE.

Actual performance results should be taken from the notebook outputs after execution.

## How to Run the Project

The notebook is designed for Google Colab.

1. Open the notebook file:
   `BRFSS_2023_Healthcare_Lifestyle_EDA_ML.ipynb`
2. Upload it to Google Colab or open it using Jupyter Notebook.
3. Connect to a Python runtime.
4. Run the installation cell to install the required libraries.
5. Execute the notebook cells in order.
6. Allow the dataset download, analysis, model training, and visualizations to complete.

**Note:** The notebook uses Google Colab-style paths such as `/content/`. If running locally, update those paths as needed.

## Project Structure

```text
BRFSS-2023-Healthcare-EDA-ML/
│
├── BRFSS_2023_Healthcare_Lifestyle_EDA_ML.ipynb
└── README.md
```

The notebook also contains code to export cleaned data and model comparison results when executed successfully.

## Key Learning Outcomes

- Working with a large public-health survey dataset
- Data cleaning and missing-value analysis
- Exploratory data analysis and visualization
- Classification and regression workflows
- Model comparison and evaluation
- Interpreting feature importance
- Understanding the limitations of predictive models

## Limitations

- Survey responses may contain missing values and special response codes.
- The notebook uses selected variables rather than every variable in the original dataset.
- Model results depend on data preparation, feature selection, sampling, and evaluation.
- Associations and feature importance do not establish causation.
- Predictions are educational and must not be used for medical diagnosis or treatment decisions.

## Disclaimer

This project is intended for educational and research purposes only. The machine learning models are not medical diagnostic tools.

## Author

**Abhishek Maity**  
B.Tech — Computer Science and Engineering (Artificial Intelligence & Data Science)  
Amity University Jharkhand

## Acknowledgements

Thanks to the U.S. Centers for Disease Control and Prevention (CDC) for providing the public BRFSS dataset and to the Python open-source community for the tools used in this project.
