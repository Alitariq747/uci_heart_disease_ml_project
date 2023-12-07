# uci_heart_disease_ml_project
Using uci famous dataset on heart disease we applied an end-to-end Machine Learning approach to analyse how different parameters can lead to an increase in chances of a heart related problem.

## Heart Disease Classification Project
This repository contains the code and documentation for a machine learning project focused on classifying heart disease using the UCI Heart Disease dataset. The project utilizes Python, Pandas, NumPy, Matplotlib, and scikit-learn for data manipulation, analysis, and model building.

## Project Overview
### Objective
The main goal of this project is to develop a machine learning model that can accurately classify the presence or absence of heart disease based on various medical and demographic features.

Dataset
The dataset used in this project is the UCI Heart Disease dataset. It contains a collection of attributes, including age, sex, cholesterol levels, and other relevant factors, for individuals to predict the presence of heart disease.

Tools and Libraries
Python
Jupyter Notebooks
Pandas for data manipulation
NumPy for numerical operations
Matplotlib for data visualization
scikit-learn for machine learning tasks.

## Getting Started
### Prerequisites
Python (3.10 recommended)
Conda for managing environments
Jupyter Notebooks
Create and activate the conda environment using:

```bash

conda env create -f environment.yml
conda activate heart-disease-env

```

## Running the Jupyter Notebook
### Clone this repository:

```bash
git clone https://github.com/Alitariq747/uci_heart_disease_ml_project.git
cd uci_heart_disease_ml_project
```
### Open and run the Jupyter notebook:

```bash
jupyter notebook end-to-end-heart-disease-classification.ipynb
```

### Data Analysis and Model Building
The Jupyter notebook end-to-end-heart-disease-classification.ipynb contains the entire process of data analysis, exploration, preprocessing, hyperparameter tuning, and machine learning model development. It provides step-by-step explanations and insights into the decision-making process.

### Results
The machine learning model achieved an accuracy of 89% on the test set after hyperparameter tuning and cross-validation. A confusion matrix and other evaluation metrics are presented in the notebook.

## Future Work
This project can be extended in the following ways:

* Experiment with different machine learning algorithms, such as XGBoost or CatBoost.
* Fine-tune hyperparameters for these algorithms for potential performance improvement.
* Explore additional features or external datasets for further enhancement.

