# House-Price-Prediction using Linear Regression
This project implements a clean and interpretable Linear Regression model to estimate house prices based on a selected subset of highly relevant features:

Square footage (GrLivArea)

Number of bedrooms (BedroomAbvGr)

Number of full bathrooms (FullBath)

Number of half bathrooms (HalfBath)

-> Problem Statement
Build a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms using a Kaggle-style dataset (provided as part of Prodigy Infotech ML Internship Project #1).

-> Dataset Files
train.csv — Training dataset with features and SalePrice as the target variable

test.csv — Test dataset with missing SalePrice

sample_submission.csv — Format for prediction output

data_description.txt — Description of all the dataset features

-> Features Used
GrLivArea: Above ground living area (square feet)

BedroomAbvGr: Number of bedrooms above ground

FullBath: Number of full bathrooms

HalfBath: Number of half bathrooms

These features were selected to build a minimal but effective regression model with better generalizability and easier deployment.

-> Tech Stack
Python 

Pandas, NumPy

Scikit-learn

Matplotlib

Jupyter Notebook

-> Model Summary
Algorithm used: Linear Regression

Evaluation metric: RMSE (Root Mean Squared Error)

Visualized model predictions with Actual vs Predicted plots

Included a real-time user input prediction system using Python console for better usability without GUI

-> How to Run
Clone the repository

Place the dataset files in the same directory

Run the Jupyter notebook:

bash
Copy
Edit
jupyter notebook HousePricePrediction_Project.ipynb
You can enter custom values (sqft, bedrooms, bathrooms) to get live price prediction

-> What Makes This Project Different
Focus on interpretability using only 4 well-selected features

Interactive user input for real-time price estimation

Clean and production-ready pipeline using scikit-learn

Perfect starting point for beginners aiming to learn ML modeling, EDA, and basic deployment

-> Future Improvements
Feature engineering and expansion

Model comparison (e.g., DecisionTree, RandomForest)

GUI using Gradio or Streamlit

Deployment on web using Flask/Streamlit

-> Acknowledgments
Dataset Source: Kaggle House Prices: Advanced Regression Techniques

Project Part of: Prodigy Infotech Machine Learning Internship
