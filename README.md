# Predictive Modeling Using Linear Regression

Build a machine learning model to predict house prices using Linear Regression and the California Housing Dataset.

---

## What This Project Does

- Loads and preprocesses housing dataset
- Trains a Linear Regression model
- Predicts house prices
- Evaluates model performance using:
  - Mean Squared Error (MSE)
  - R² Score
- Visualizes Actual vs Predicted values

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

```bash
ml_project/
│── predictive_model.py      # Main ML code
│── regression_performance.png   # Output graph
│── requirements.txt         # Required libraries
│── .gitignore               # Ignore unnecessary files
│── README.md                # Project documentation


How to Run
1. Clone the Repository
Bash
git clone https://github.com/your-username/ml_project.git
cd ml_project
2. Install Dependencies
Bash
pip install -r requirements.txt
3. Run the Project
Bash
python predictive_model.py
Sample Output
Python
Training Linear Regression Model...

Mean Squared Error (MSE): 0.6785
R-squared Score (Accuracy Metric): 49.12%

Visualization saved as 'regression_performance.png'
