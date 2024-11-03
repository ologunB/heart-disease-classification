# Predicting Heart Disease Using Machine Learning

This project explores the use of various Python-based machine learning and data science libraries to build a model capable of predicting whether or not an individual has heart disease based on their medical attributes.

## Table of Contents

1. [Problem Definition](#problem-definition)
2. [Data](#data)
3. [Evaluation](#evaluation)
4. [Features](#features)
5. [Modelling](#modelling)
6. [Experimentation](#experimentation)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [License](#license)

## Problem Definition

In this project, we aim to answer the following question:

**Given clinical parameters about a patient, can we predict whether or not they have heart disease?**

## Data

The original dataset used in this analysis is the Cleveland Heart Disease dataset obtained from the UCI Machine Learning Repository. You can access it [here](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

Additionally, a version of this dataset is available on Kaggle, which can be found [here](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).

## Evaluation

The model's performance will be evaluated using various metrics such as accuracy, precision, recall, and F1-score. A confusion matrix will also be utilized to visualize the performance of the model.

## Features

The dataset includes several features that are critical for predicting heart disease, including but not limited to:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Serum Cholesterol
- Fasting Blood Sugar
- Resting Electrocardiographic Results
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- Oldpeak
- Slope of the Peak Exercise ST Segment
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia
- Target Variable (presence or absence of heart disease)

## Modelling

We will employ various machine learning algorithms, including but not limited to:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- Neural Networks

Hyperparameter tuning will also be conducted to optimize the models for better performance.

## Experimentation

Through this notebook, we will document the different experiments and iterations made during the model-building process, including data preprocessing, feature engineering, and model evaluation.

## Installation

To get started with this project, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook or any IDE of your choice
- Required Python libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

## Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the notebook to execute the analysis and model training.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
