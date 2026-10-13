# Linear Regression Prediction Project

## Overview

This project uses Linear Regression to predict outcomes from two datasets: Ice Cream Sales and Advertising Sales. It includes model evaluation and interactive web interfaces built with Flask and Gradio.

## Project Objectives

* Build linear regression models using Python.
* Predict ice cream profits based on temperature.
* Predict sales based on TV advertising expenditure.
* Evaluate model performance using R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
* Create interactive interfaces for making predictions.

## Datasets

1. **Ice Cream Sales:** Uses `Temperature` to predict `Ice Cream Profits`.
2. **Advertising:** Uses `TV` advertising expenditure to predict `Sales`.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Flask
* Gradio
* HTML

## Model Performance

| Dataset         | R² Score |   MAE |   MSE |
| --------------- | -------: | ----: | ----: |
| Advertising     |    0.803 | 1.950 | 6.101 |
| Ice Cream Sales |    0.984 | 1.845 | 5.294 |

*These are the results obtained during development; results may vary if the data or model changes.*

## Project Structure

```text
linear-regression-project/
├── app.py
├── models.py
├── gradio_app.py
├── requirements.txt
├── templates/
│   └── index.html
└── README.md
```

The Jupyter Notebook and CSV datasets may also be included if required for the assignment.

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

Make sure the CSV datasets are available at the paths expected by `models.py`.

## Running the Flask Application

Run:

```bash
python app.py
```

Open `http://127.0.0.1:5000` in your browser.

## Running the Gradio Application

Run:

```bash
python gradio_app.py
```

Open the local URL displayed in the terminal.

## Evaluation Metrics

* **R² Score:** Measures how much variation in the target variable is explained by the model.
* **MAE:** Measures the average absolute prediction error.
* **MSE:** Measures the average squared prediction error.

## Author
Anusha Azam
