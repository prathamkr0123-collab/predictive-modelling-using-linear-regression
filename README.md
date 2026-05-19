Predictive Modeling Using Linear Regression
A Machine Learning project that predicts California housing prices using the Linear Regression algorithm. This project demonstrates the complete workflow of a regression model, including data preprocessing, model training, evaluation, and visualization.
Project Overview
This project uses the California Housing dataset provided by Scikit-learn to build a predictive model for housing prices.
The workflow includes:
Loading and preparing the dataset
Selecting important features
Splitting data into training and testing sets
Training a Linear Regression model
Predicting housing prices
Evaluating model performance
Visualizing actual vs predicted values
Features
Simple and beginner-friendly ML project
Uses real-world housing dataset
Implements Linear Regression
Calculates evaluation metrics:
Mean Squared Error (MSE)
R² Score
Generates performance visualization graph
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Dataset Information
Dataset Used:
California Housing Dataset
Features Used
Feature
Description
MedInc
Median Income
HouseAge
House Age
AveRooms
Average Number of Rooms
Target Variable
Target
Description
MedHouseVal
Median House Value
Project Structure
Plain text
linear-regression-project/
│
├── linear_regression.py         # Main project file
├── regression_performance.png   # Output visualization
├── requirements.txt             # Required libraries
├── .gitignore                   # Ignored files for Git
└── README.md                    # Project documentation
Installation
Install the required Python libraries:
Bash
pip install numpy pandas matplotlib seaborn scikit-learn
Or install using requirements.txt:
Bash
pip install -r requirements.txt
How to Run the Project
Run the Python file:
Bash
python linear_regression.py
Or execute the notebook in Jupyter Lab/Notebook.
Model Training
The project trains a Linear Regression model using:
Python
model = LinearRegression()
model.fit(X_train, y_train)
The model learns the relationship between housing features and house prices.
Model Evaluation
The project evaluates model performance using:
Mean Squared Error (MSE)
R² Score
Example output:
Plain text
Training Linear Regression Model...

Mean Squared Error (MSE): 0.6589
R-squared Score (Accuracy Metric): 49.72%

Visualization saved as 'regression_performance.png'
Visualization
The project generates a scatter plot comparing:
Actual Values
Predicted Values
Perfect Prediction Line
This helps visualize the accuracy of predictions.
Future Improvements
Use all dataset features for better accuracy
Apply feature scaling
Experiment with advanced regression models:
Random Forest Regressor
Decision Tree Regressor
XGBoost Regressor
Learning Outcomes
By completing this project, you will learn:
Basics of Machine Learning
Regression algorithms
Data preprocessing
Model evaluation techniques
Data visualization in Python
Author
Pratham Kumar
License
This project is open-source and available for educational purposes.
