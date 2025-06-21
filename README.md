# House-price-prediction
Overview:
This project predicts house sale prices using regression techniques. It covers data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation. The goal is to build a model that accurately estimates house prices.

Features:

Cleans and processes raw data

Visualizes distributions and correlations

Trains multiple regression models (Linear Regression, Random Forest, XGBoost, etc.)

Evaluates models using RMSE, MAE, R²

Supports hyperparameter tuning and model comparison

Setup Steps:

Clone the repo:
git clone https://github.com/srilasya-s/House-price-prediction
cd House-price-prediction

(Optional) Create a virtual environment:
python -m venv venv
source venv/bin/activate (Linux/Mac)
venv\Scripts\activate (Windows)

Install required libraries:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook
Open house-price-prediction.ipynb and run the cells.

Libraries Used:

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost (if used)

Project Structure:

data/: training and test CSVs

notebooks/: main notebook

src/: optional scripts (e.g. preprocessing, modeling)

requirements.txt

README.md

Usage Flow:

Load and clean the data

Visualize relationships

Engineer and select features

Train models and evaluate

Generate predictions on test data

Sample Evaluation Results:
Linear Regression → R²: 0.72
Random Forest → R²: 0.84
XGBoost → R²: 0.87

Repo Link:
https://github.com/srilasya-s/House-price-prediction
