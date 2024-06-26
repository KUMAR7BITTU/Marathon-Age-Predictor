# Marathon Age Prediction
This repository contains a Jupyter Notebook for predicting the age of an athlete based on the first and second half marathon splits from the 2024 Boston Marathon dataset. The project involves data preprocessing, model training, and evaluation using a Linear Regression model.

# Introduction
This project aims to predict the age of marathon runners using their half marathon split times. By analyzing the provided dataset, we apply machine learning techniques to create a predictive model.

# Dataset
The dataset used in this project is the "2024 Boston Marathon Weather and Splits" dataset. It includes:
1. first_half_split: The time for the first half of the marathon.
2. second_half_split: The time for the second half of the marathon.
3. age: The age of the athlete.
You can download the dataset from Kaggle

# Installation
To run this project locally, follow these steps:

1. Clone the repository:-
git clone https://github.com/KUMAR7BITTU/Marathon-Age-Predictor.git

2. Install the necessary packages:-
pip install pandas numpy scikit-learn matplotlib seaborn
Download the dataset

3. Download the dataset from the link :- https://www.kaggle.com/datasets/runningwithrock/2024-boston-marathon-weather-and-splits
Place the dataset file in the root directory of this project.

# Usage
Open the Jupyter Notebook and run the cells to see the data preprocessing, model training, and evaluation steps.

1. Launch Jupyter Notebook
2. Open and run marathon_age_prediction.ipynb

# Model
We use a Linear Regression model to predict the age of the marathon runners. The model is trained using the first and second half split times as features.

# Results
The performance of the model is evaluated using the following metrics:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Here are the results:

Mean Absolute Error: 10.275231219868
Mean Squared Error: 152.3445266201889
Root Mean Squared Error: 12.342792496845634
R-squared: 0.06069760548332659

# Contributing
Contributions are welcome! Please open an issue to discuss what you would like to change.
