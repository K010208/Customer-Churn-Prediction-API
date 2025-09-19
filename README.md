# Customer Churn Prediction API

A complete **Machine Learning project** to predict customer churn, built with **Python, scikit-learn, and Flask**. This project includes a REST API for real-time predictions and a Jupyter Notebook for exploratory analysis.  

---

## **Project Overview**

Customer churn is a critical metric for businesses. This project uses a **Random Forest classifier** trained on sample customer data to predict whether a customer is likely to churn.  

Key features:  
- Train ML model on customer features  
- Save model using `pickle`  
- REST API with Flask for real-time predictions  
- Jupyter Notebook for exploratory data analysis  

---

## **Folder Structure**

Customer-Churn-Prediction-API/
├── app.py # Flask API
├── model.py # Train & save ML model
├── requirements.txt # Required packages
├── README.md # Project documentation
├── data/
│ └── sample_data.csv # Sample dataset
└── notebooks/
└── exploratory_analysis.ipynb # Data analysis notebook

yaml


## **Setup Instructions**

1. Download or clone the repository.  
2. Install required packages:

```bash
pip install -r requirements.txt
Train the model:


python model.py
Run the Flask API:


python app.py
Test the API using Postman or Python requests:

python
import requests

url = "http://127.0.0.1:5000/predict"
data = {"Feature1": 40, "Feature2": 0, "Feature3": 20}
response = requests.post(url, json=data)
print(response.json())
Exploratory Analysis
Open the notebook notebooks/exploratory_analysis.ipynb to explore the dataset.

Quick insights and descriptive statistics are included.

Technologies Used
Python 3

Pandas & NumPy

scikit-learn

Flask

Jupyter Notebook

Author
Khushi Chauhan

Email: khushiichauhan2506@gmail.com

GitHub: https://github.com/K010208
