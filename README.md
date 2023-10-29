# Tunning_na_pr-tica--Bank_loan_modeling

# Bank Personal Loan Modeling

This repository contains a Python script for modeling personal loan data using Decision Trees and Random Forest classifiers. It includes data preprocessing, model training, hyperparameter tuning, and performance evaluation.

## Getting Started

To get started, you need to have Python and Jupyter Notebook installed. You can install the required Python packages using pip:

```bash
pip install numpy pandas scikit-learn

Data Loading and Preprocessing
The data is loaded from an Excel file and preprocessed to handle missing values. Categorical variables are one-hot encoded, and the dataset is split into training and testing sets.

Decision Tree Classifier
A Decision Tree Classifier is trained on the training data. The model's accuracy is evaluated on both the training and testing datasets.

Hyperparameter Tuning with Grid Search
Grid Search is used to optimize the hyperparameters of the Decision Tree Classifier. The best hyperparameters are selected based on the 'accuracy' metric, and the model is retrained with the optimal settings. The accuracy of the tuned model is evaluated on the testing data.

Random Forest Classifier
A Random Forest Classifier is trained on the training data. Similar to the Decision Tree, the accuracy of the Random Forest model is evaluated on both the training and testing datasets.

Hyperparameter Tuning for Random Forest
Grid Search is again used to optimize the hyperparameters of the Random Forest Classifier. The best hyperparameters are determined based on the 'accuracy' metric, and the model is retrained with the optimal settings. The accuracy of the tuned Random Forest model is evaluated on the testing data.

Conclusion
This repository provides a comprehensive example of data preprocessing, model training, hyperparameter tuning, and performance evaluation for personal loan prediction using Decision Trees and Random Forest. You can adapt this code for your own datasets and classification tasks.

License
This project is licensed under the MIT License - see the LICENSE file for details.
