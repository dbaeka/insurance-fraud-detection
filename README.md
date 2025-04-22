# Mobile Money Fraud Detection

This repository contains a PCA and machine learning project focused on detecting mobile money transaction fraud using
various algorithms. The project is designed to provide insights into the effectiveness of different models in
identifying fraudulent transactions.

## Project Overview

The project is structured to include data preprocessing, model training, evaluation, and visualization. The main
components of the project are as follows:

- **Data Preprocessing**: This step involves cleaning the dataset, handling missing values, and encoding categorical
  variables.
- **Model Training**: Several machine learning algorithms are implemented, including Logistic Regression, Decision
  Trees, Random Forests, and Gradient Boosting.
- **Model Evaluation**: The models are evaluated using metrics such as accuracy, precision, recall, and F1-score. A
  confusion matrix is also generated to visualize the performance of the models.
- **Visualization**: The project includes visualizations to help understand the distribution of features and the
  performance of the models.
- **Feature Importance**: The project includes a feature importance analysis to identify the most significant features
  contributing to the model's predictions.
- **PCA Analysis**: The project includes a PCA analysis to visualize the data in a lower-dimensional space.

## Requirements

Python **3.11** or higher is required to run this project. You can create a virtual environment and install the required
packages using the following commands:

```bash
# Create a virtual environment
python -m venv venv
# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
# Install the required packages
pip install -r requirements.txt
```

## Dataset

The dataset used in this project is a synthetic mobile money dataset from Mendeley. It contains various features related
to mobile money transactions, including amount, transaction type, and whether the transaction was fraudulent or not. The
dataset is available in the `data` directory when loaded.

## Project Structure

```plaintext
mobile-money-fraud-detection/
├── data/
│   ├── Synthetic Mobile Money Transaction Dataset
│       ├── synthetic_mobile_money_transaction_dataset.csv
├── Mobile Money Fraud Detection.ipnyb
├── requirements.txt
├── README.md
```

## Usage

To run the project, open the `Mobile Money Fraud Detection.ipynb` notebook in Jupyter Notebook or any compatible IDE.
The notebook contains all the code for data preprocessing, model training, evaluation, and visualization. You can run
each cell step by step to see the results.

