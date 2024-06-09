# Fraud-Detection-using-CabBooster-RandomForest-DecisionTree

## Overview
This project aims to detect fraudulent transactions using machine learning algorithms, specifically CabBooster, RandomForest, and DecisionTree. The dataset used for training and evaluation contains features related to transactions, and the target variable indicates whether a transaction is fraudulent or not.

## Dependencies
- Python 3.x
- CabBooster
- scikit-learn
- pandas
- numpy

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your_username/fraud-detection.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
The dataset used for this project is stored in `data/transactions.csv`. It contains the following columns:
- Feature1
- Feature2
- ...
- Target (isFraud)

## Usage
1. Navigate to the project directory:
   ```bash
   cd fraud-detection
   ```
2. Run the `main.py` script to train and evaluate the machine learning models:
   ```bash
   python main.py
   ```
3. The script will output the performance metrics of each model (accuracy, precision, recall, F1-score, etc.) and optionally save the trained models to the `models/` directory.

## Model Evaluation
The performance of each model is evaluated using various metrics, including accuracy, precision, recall, F1-score, and confusion matrix. The evaluation results are displayed in the console output and can be further analyzed to determine the effectiveness of each model in detecting fraudulent transactions.

## Future Improvements
- Explore additional features or feature engineering techniques to improve model performance.
- Experiment with other machine learning algorithms or ensemble methods.
- Conduct hyperparameter tuning to optimize the models' performance.
- Deploy the best-performing model as a real-time fraud detection system.
