# Customer Churn Prediction Analysis using Machine Learning

![Churn Prediction](churn.png)

This repository contains a Customer Churn Prediction Analysis project that utilizes machine learning to predict customer churn for a business. Churn prediction is a critical task for businesses as it helps in retaining valuable customers and increasing profitability. This README file provides an overview of the project, its contents, and instructions on how to use and contribute to it.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Customer churn, also known as customer attrition, is a critical metric for businesses in various industries. It refers to the percentage of customers who stop using a company's products or services during a certain time period. Predicting customer churn is essential for businesses to develop strategies for customer retention and growth. This project uses machine learning techniques to predict customer churn based on historical customer data.

## Project Overview

The Customer Churn Prediction Analysis project includes the following components:

- Data collection and preprocessing: The project starts by collecting customer data, cleaning it, and preparing it for machine learning.

- Feature engineering: Creating relevant features and transforming the data for model training.

- Model selection: Choosing and training machine learning models to predict customer churn.

- Evaluation: Assessing model performance and determining how well the models predict customer churn.

- Deployment: Deploying the best-performing model for real-time customer churn prediction.

## Project Structure

The project directory structure is organized as follows:

```
Customer-Churn-Prediction-Analysis/
    ├── data/
    │   ├── raw_data.csv
    │   ├── processed_data.csv
    ├── notebooks/
    │   ├── Data_Preprocessing.ipynb
    │   ├── Model_Training.ipynb
    │   ├── Model_Evaluation.ipynb
    ├── src/
    │   ├── data_preprocessing.py
    │   ├── model_training.py
    │   ├── evaluation.py
    ├── churn_prediction_app/
    │   ├── app.py
    │   ├── templates/
    │   │   ├── index.html
    ├── README.md
    ├── requirements.txt
```

- `data`: This directory contains the raw and processed data in CSV format.

- `notebooks`: Jupyter notebooks for data preprocessing, model training, and model evaluation.

- `src`: Python scripts for data preprocessing, model training, and evaluation.

- `churn_prediction_app`: A folder containing a simple web application for real-time churn prediction using the best model.

- `README.md`: The file you are currently reading, providing an overview of the project.

- `requirements.txt`: Lists the necessary Python packages and their versions for running this project.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following software and libraries installed:

- Python (3.6+)
- Jupyter Notebook (optional but recommended)
- Required Python libraries (install via `pip`):
  - pandas
  - scikit-learn
  - matplotlib
  - flask (for the web application)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/Customer-Churn-Prediction-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Customer-Churn-Prediction-Analysis
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**: Open and run the `Data_Preprocessing.ipynb` notebook to clean and preprocess the raw customer data. Alternatively, you can use the scripts in the `src` directory.

2. **Model Training**: Use the `Model_Training.ipynb` notebook to train machine learning models to predict customer churn. You can also run the scripts in the `src` directory for this purpose.

3. **Model Evaluation**: Evaluate the model's performance using the `Model_Evaluation.ipynb` notebook. This notebook also contains model deployment instructions.

4. **Web Application**: The `churn_prediction_app` directory contains a simple Flask web application (`app.py`) for real-time customer churn prediction using the best model. To run the web app, navigate to the `churn_prediction_app` directory and execute:

   ```bash
   python app.py
   ```

   You can access the web app in your browser at `http://localhost:5000`.

## Data

The `data` directory contains the customer data required for the analysis:

- `raw_data.csv`: The raw customer data obtained from the business.

- `processed_data.csv`: The cleaned and preprocessed data used for model training and evaluation.

Ensure that the raw data is updated periodically to keep the model relevant.

## Model Training

The `notebooks` and `src` directories contain the tools and scripts required for training machine learning models. You can experiment with different algorithms, hyperparameters, and feature engineering techniques to improve model performance.

## Evaluation

Model evaluation is crucial to determine the model's effectiveness in predicting customer churn. The `Model_Evaluation.ipynb` notebook provides an in-depth analysis of the models' performance metrics, such as accuracy, precision, recall, and F1-score. It also explains how to deploy the best model for real-time prediction.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Make your changes and test them.

4. Create a pull request with a detailed description of your changes.

Please ensure your code follows best practices and includes tests where necessary.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



![Customer Churn Prediction](prediction.png)
