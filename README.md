# Sale-forecasting-
Sales Forecasting - Wiseanalytics Data Science Internship

This project is a part of the Wiseanalytics Data Science Internship Assessment, focused on sales forecasting using historical data. The goal is to analyze, preprocess, and model the data to predict future sales effectively using regression techniques.

Project Overview

The notebook walks through a comprehensive data science workflow:
	•	Data Loading & Exploration
	•	Data Cleaning & Preprocessing
	•	Feature Engineering
	•	Model Building (Linear Regression)
	•	Evaluation of Model Performance

Dataset

The dataset includes the following columns:
	•	Date: The date of each sales entry
	•	Sales: The amount of sales on the corresponding date

Sales are recorded daily and used to predict future trends using time-series regression techniques.

Key Steps
	1.	Exploratory Data Analysis (EDA)
	•	Checked for missing values and data types
	•	Converted Date column to datetime format
	•	Plotted sales trends over time
	2.	Feature Engineering
	•	Extracted time-based features: day, month, year, and weekday from Date
	•	Removed the original Date column to use engineered features for modeling
	3.	Modeling
	•	Trained a Linear Regression model using scikit-learn
	•	Evaluated the model using Mean Absolute Error (MAE) and R² Score
	4.	Results
	•	MAE: ~241.39
	•	R² Score: ~0.69
The model showed decent performance for a simple regression approach, leaving room for improvement using more advanced time-series techniques.

Technologies Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib & Seaborn
	•	Scikit-learn
	•	Jupyter Notebook
