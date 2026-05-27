Earthquake Damage Prediction

Overview
This project uses machine learning to predict earthquake damage grades based on building features. The model is built using logistic regression and evaluated on accuracy, F1 score, and confusion matrix metrics.

Dependencies
- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

Data
The dataset used contains building features and damage grades.

Code Structure
- Data loading and preprocessing
- Baseline model (Dummy Classifier)
- Logistic Regression model with undersampling (RandomUnderSampler)
- Model evaluation (accuracy, F1 score, confusion matrix, classification report)

Usage
1. Clone the repo and install dependencies.
2. Mount your Google Drive in Colab and update the file path.
3. Run the notebook to train and evaluate the model.

Results
- Baseline accuracy: ~0.33
- Logistic Regression accuracy: ~0.55
- Confusion matrix and classification report available in the notebook.

Notes
- Data imbalance was addressed using RandomUnderSampler.
- One-hot encoding was applied to non-numeric columns.
- Model performance can be improved with hyperparameter tuning and feature engineering.
