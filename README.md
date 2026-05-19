California Housing Price Prediction using Linear Regression
Project Overview

This project demonstrates a simple Machine Learning Regression Model using Linear Regression to predict housing prices from the California Housing dataset.

The project includes:

Data loading and preprocessing
Feature selection
Model training
Prediction
Performance evaluation
Visualization of results
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Dataset

The project uses the built-in California Housing dataset available in Scikit-learn.

Features Used
Feature	Description
MedInc	Median income
HouseAge	Age of houses
AveRooms	Average number of rooms
Target Variable
Target	Description
MedHouseVal	Median house value
Project Workflow
1. Import Libraries

Required libraries for:

Data handling
Visualization
Machine Learning
2. Load Dataset

The California Housing dataset is loaded using:

from sklearn.datasets import fetch_california_housing
3. Data Preparation
Features (X) and target (y) are selected
Dataset is split into training and testing sets
4. Train Model

A Linear Regression model is trained using:

LinearRegression()
5. Evaluate Model

Performance metrics used:

Mean Squared Error (MSE)
R² Score
6. Visualization

A scatter plot compares:

Actual values
Predicted values
Output Example
Training Linear Regression Model...

Mean Squared Error (MSE): 0.6589
R-squared Score (Accuracy Metric): 49.72%

Visualization saved as 'regression_performance.png'
Performance Visualization

The model generates a graph showing:

Actual house prices
Predicted house prices
Perfect prediction reference line

Saved as:

regression_performance.png
How to Run the Project
Step 1: Install Required Libraries
pip install numpy pandas matplotlib seaborn scikit-learn
Step 2: Run the Python File
python linear_regression.py

Or run it in Jupyter Notebook.

Project Structure
project-folder/
│
├── linear_regression.py
├── regression_performance.png
└── README.md
Future Improvements
Use all dataset features for better accuracy
Apply feature scaling
Try advanced regression algorithms:
Random Forest Regressor
XGBoost
Decision Tree Regressor
Learning Outcomes

Through this project, you will learn:

Basics of Regression
Model Training and Testing
Performance Evaluation
Data Visualization
Machine Learning Workflow
Author

Pratham Kumar

License

This project is open-source and free to use for educational purposes.
