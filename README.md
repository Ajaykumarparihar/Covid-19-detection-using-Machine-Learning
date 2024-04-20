# COVID-19 Detection Using Machine Learning

This repository contains code for predicting COVID-19 infection using machine learning algorithms based on patient symptoms and history.

## Overview

The project aims to predict the likelihood of a person being infected with COVID-19 based on various symptoms and risk factors. It utilizes machine learning algorithms such as Logistic Regression, K-Nearest Neighbors, Random Forest Classifier, etc., to analyze patient data and make predictions.

## Dataset

The dataset used for training and testing the models is `Covid Dataset.csv`. It contains various features such as breathing problems, fever, dry cough, sore throat, travel history, contact with COVID-19 patients, etc., along with the target variable indicating the presence or absence of COVID-19 infection.

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- scikit-learn
- matplotlib
- plotly
- colorama

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/Covid-19-detection-using-Machine-Learning.git
    cd Covid-19-detection-using-Machine-Learning
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook or Python script to train the models and make predictions.

## Usage

1. Run the Jupyter Notebook or Python script `covid_detection.py` to train the machine learning models and perform predictions.

2. Follow the instructions provided in the console or script for entering patient symptoms and history to predict COVID-19 infection.

## Results

The models are evaluated based on various performance metrics such as accuracy, ROC AUC score, R2 score, mean squared error, etc. The results are visualized using plots and presented in the console.

## Contributors

Ajay Kumar(https://github.com/your_username)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
