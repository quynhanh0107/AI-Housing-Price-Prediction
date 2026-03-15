California Housing Price Prediction 🏡
📌 Project Overview
This repository contains an end-to-end machine learning project that predicts median housing prices in California districts.

This is a personal learning project based on Chapter 2 of the highly acclaimed textbook Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurélien Géron. It demonstrates a complete machine learning workflow, from data ingestion to model fine-tuning.

📊 The Dataset
The dataset used is the California Housing Prices dataset from the StatLib repository, which is based on data from the 1990 California census.

Features: Include metrics such as population, median income, housing median age, and geographical coordinates for various districts.

Target Variable: median_house_value

🚀 Project Workflow
Following the end-to-end framework outlined in the book, this project covers the following steps:

Framing the Problem: Defining the objective, current solutions, and selecting the right performance measure (Root Mean Squared Error - RMSE).

Fetching the Data: Automating the download and extraction of the dataset.

Exploratory Data Analysis (EDA): Visualizing geographical data, looking for correlations, and experimenting with attribute combinations.

Data Preparation: Building a robust data preprocessing pipeline using Scikit-Learn.

Handling missing values (SimpleImputer)

Encoding categorical attributes (OneHotEncoder)

Feature scaling (StandardScaler)

Custom transformers for adding combined attributes.

Training and Evaluating Models: Testing various algorithms including:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Fine-Tuning the Model: Using GridSearchCV and RandomizedSearchCV to find the best hyperparameters for the Random Forest model.

🛠️ Technologies & Libraries Used
Python 3

Jupyter Notebook (for interactive development)

Pandas (data manipulation)

NumPy (numerical computations)

Matplotlib / Seaborn (data visualization)

Scikit-Learn (machine learning models and pipelines)

📈 Results
Note: Update this section with your actual findings!

The Decision Tree model heavily overfit the training data.

The Random Forest proved to be the most promising model.

After fine-tuning using Grid Search, the final Random Forest model achieved an RMSE of approximately [$X,XXX] on the test set.
