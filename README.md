Predictive Modeling Using Linear Regression

Build a machine learning model to predict California housing prices using Linear Regression.

What This Project Does
Loads the California Housing dataset
Trains a Linear Regression model
Predicts housing prices
Evaluates model performance using:
Mean Squared Error (MSE)
R² Score
Visualizes prediction performance using scatter plots
Project Structure
linear-regression-project/
│
├── linear_regression.py        # Main Python code
├── regression_performance.png  # Output visualization
├── requirements.txt            # Required libraries
├── .gitignore                  # Ignored files
└── README.md                   # Project documentation
How to Run
1. Clone the Repository
git clone https://github.com/your-username/linear-regression-project.git

cd linear-regression-project
2. Install Dependencies
pip install -r requirements.txt

Or manually install:

pip install numpy pandas matplotlib seaborn scikit-learn
3. Run the Project
python linear_regression.py

Or run it in Jupyter Notebook.

Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Dataset Information

Dataset used:

California Housing Dataset from Scikit-learn
Features Used
MedInc → Median Income
HouseAge → House Age
AveRooms → Average Rooms
Target
MedHouseVal → Median House Value
Model Performance

Example output:

Training Linear Regression Model...

Mean Squared Error (MSE): 0.6589
R-squared Score (Accuracy Metric): 49.72%

Visualization saved as 'regression_performance.png'
Output Visualization

The model generates a graph comparing:

Actual Values
Predicted Values
Perfect Prediction Line

Saved as:

regression_performance.png
Future Improvements
Use all available dataset features
Apply feature scaling
Try advanced regression models:
Random Forest Regressor
XGBoost
Decision Tree Regressor
Learning Outcomes

This project helps understand:

Machine Learning basics
Regression algorithms
Data preprocessing
Model evaluation
Data visualization
Author

Pratham Kumar
