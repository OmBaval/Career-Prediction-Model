# Career Prediction Model using Deep Learning

## Overview

This Jupyter notebook presents a Career Prediction Model using Deep Learning. The model utilizes Artificial Neural Networks (ANNs) and is trained on an anonymized dataset containing 20,000 entries and 38 features. The dataset includes academic data, personal interest data, knowledge data, communication skill data, teamwork data, problem-solving data, and self-management data.

## Installation

```bash
git clone https://github.com/your-username/career-prediction-model.git
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Pickle
- Warnings
- Scikit-learn
- Imbalanced-learn
- mpl_toolkits
- scipy

## Dataset

The dataset, named "roo_data.csv," is loaded and analyzed to understand its structure and content. It consists of 20,000 entries and 38 features, with 14 numeric and the remaining non-numeric features.

## Preprocessing

1. One-Hot Encoding: Numeric and non-numeric features are one-hot encoded.
2. Label Encoding: The target variable is label encoded for model training.
3. Class Clubbing: The target variable classes are grouped into 11 categories to balance the dataset.
4. Oversampling: Random oversampling is performed to address class imbalance.

## Model Training

The Multi-Layer Perceptron (MLP) Classifier is employed with the following parameters:
- Activation function: tanh
- Hidden layers: 50, 50, 50
- Solver: Adam

The model is trained on 80% of the oversampled dataset.

## Model Evaluation

The model's performance is evaluated using confusion matrices, classification reports, and accuracy scores for both the training and testing datasets.

## Prediction on New Data

A sample input is provided to demonstrate how the trained model predicts the suggested job role category and potential roles.

## PCA Analysis

Principal Component Analysis (PCA) is applied for 2D and 3D visualization of the dataset.

## Conclusion

The model performs well, suggesting job role categories and roles based on the input features. PCA analysis filed toprovides insights into the dataset's structure. Thus, the raw model without PCA is considered

## Author

- OM BAVAL
- Email: ombaval@gmail.com
- LinkedIn: [https://www.linkedin.com/in/ombaval/](https://www.linkedin.com/in/ombaval/)

This project is licensed under the [MIT License](LICENSE).

Feel free to reach out for any questions or further collaboration.
