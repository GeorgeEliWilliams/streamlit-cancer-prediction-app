# Breast Cancer Prediction App

## Overview

This project aims to develop a web application for breast cancer prediction using machine learning techniques. The application provides users with an intuitive interface to input cell nuclei measurements and obtain predictions regarding the likelihood of breast cancer malignancy.

A live version of the application can be found on [Cancer Predictor App](http://172.20.10.4:8501/).

## Features

1. Allows users to input cell nuclei measurements via an interactive sidebar.
2. Utilizes a logistic regression model trained on breast cancer data to predict malignancy.
3. Provides visualizations of cell nuclei measurements and prediction results.
4. Offers insights into the predictive performance through accuracy scores and classification reports.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/GeorgeEliWilliams/streamlit-cancer-prediction-app.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Ensure you have installed the required dependencies as per the installation instructions.
2. Run the Streamlit app:
```bash
streamlit run app.py
```
3. Access the app via your web browser at 'http://172.20.10.4:8501/'.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Plotly