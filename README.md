Overview

Churn Analysis is a project aimed at identifying customers who are likely to leave (churn) a business. By analyzing customer data, visualizing key patterns, and optionally building predictive models, businesses can take proactive measures to improve customer retention.

Features

✅ Data Cleaning & Preprocessing

✅ Exploratory Data Analysis (EDA)

✅ Data Visualisation of key metrics (age, tenure, churn rate, etc.)

✅ Identification of churn patterns

✅ Optional Machine Learning Model for churn prediction

Dataset

The project uses a dataset containing customer information, including:

Demographics: Age, Gender, Location

Account details: Tenure, Subscription Type, Usage Patterns

Churn Status: Whether the customer left the service

Note: Replace the dataset path in the notebook before running.

Requirements

Python 3.x

Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn (for ML model)

Install dependencies with:

pip install -r requirements.txt

Usage

Clone the repository:

git clone <repository_link>


Navigate to the project folder:

cd churn_analyse


Open the Jupyter Notebook:

Jupyter Notebook churn_analysis.ipynb


Explore visualisations, insights, and predictions.

Project Structure
churn_analyse/
│
├── churn_analysis.ipynb       # Main notebook with analysis
├── data/                      # Dataset folder
├── images/                    # Saved visualizations
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

Insights

Visualisations reveal churn patterns across customer demographics and account types.

Correlation analysis identifies key factors driving churn.

Machine Learning models can predict potential churners to improve retention strategies.


Author

Gourav Jangid
BSc Data Science Student

License

This project is for academic and learning purposes only.
