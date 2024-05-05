# Predictive Rainfall Model for Hong Kong

## Overview
This repository contains the files and resources for a predictive model aimed at dynamically forecasting rainfall in Hong Kong. The model utilizes a series of meteorological indices, which are key factors likely to influence rainfall.

## Contents
- **Model.ipynb**: A Jupyter Notebook containing the complete code for building and evaluating the predictive model.
- **Training.csv**: The dataset used for training the model, containing various meteorological indices and historical rainfall data.

## Getting Started
Follow these steps to set up and run the project:

1. **Install Python**:
   Ensure you have Python installed on your system.

2. **Install Jupyter**:
   Run the following command in your command line:
   pip install jupyter
   
3. **Clone the Repository**:
Clone this repository to your local machine using:
git clone [[URL]](https://github.com/CynthiaLIiii/HK-Rainfall-Prediction)

4. **Launch Jupyter Notebook**:
Navigate to the cloned directory and start Jupyter Notebook by running:
jupyter notebook


5. **Open the Notebook**:
Open `Model.ipynb` in the Jupyter interface to view and run the cells.

## Model Details
The predictive model, detailed in `Model.ipynb`, is developed using Python within a Jupyter Notebook environment. The notebook provides a comprehensive walkthrough of the following stages:

- **Data Loading**: Importing data from `Training.csv`.
- **Data Preprocessing**: Cleaning and preparing the data for modeling.
- **Feature Selection**: Identifying and selecting significant predictors for the model.
- **Model Building**: Constructing the model to forecast rainfall.
- **Model Evaluation**: Assessing the model's performance with various metrics.
