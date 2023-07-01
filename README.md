# Diabetic Patient Prediction

This project aims to predict diabetic patients using three different classification algorithms: Logistic Regression, Support Vector Classifier, and Random Forest Classifier. The project is implemented using Python and leverages scikit-learn, a popular machine learning library.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Diabetes is a chronic disease that affects millions of people worldwide. Early detection and prediction of diabetic patients can significantly improve their quality of life and reduce the risk of complications. This project utilizes three different classification algorithms to predict whether a person is diabetic or not based on various features such as age, body mass index (BMI), blood pressure, etc. Logistic Regression, Support Vector Classifier, and Random Forest Classifier are implemented and compared to evaluate their performance.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/shaadclt/Diabetic-Patient-Prediction.git
   ```
2. Navigate to the project directory:
   ```
   cd Diabetic-Patient-Prediction
   ```

## Usage
1. Prepare your dataset by placing it in the project directory or specify the file path in the code.
2. Open the Jupyter notebook or Python script that corresponds to the algorithm you want to run.
3. Follow the instructions and run the code to train and evaluate the classifier.
4. Adjust the hyperparameters and experiment with different settings as desired.

## Dataset
The dataset used in this project contains various features of patients, such as age, BMI, blood pressure, glucose level, etc., along with their diabetic status (0 for non-diabetic and 1 for diabetic). The dataset used here is an example, and you can replace it with your own dataset. Make sure the dataset is in a suitable format for scikit-learn classifiers.

## Methods
This project employs three different classification algorithms to predict diabetic patients:

1. **Logistic Regression**: Logistic Regression is a commonly used algorithm for binary classification. It models the probability of an instance belonging to a certain class using a logistic function.

2. **Support Vector Classifier**: Support Vector Classifier (SVC) is a powerful algorithm that can perform both linear and non-linear classification. It aims to find the best hyperplane that separates the data points of different classes.

3. **Random Forest Classifier**: Random Forest Classifier is an ensemble learning method that constructs a multitude of decision trees at training time and outputs the class that is the mode of the classes predicted by individual trees.

## Results
The performance of each classifier is evaluated using various metrics such as accuracy, precision, recall, and F1-score. The results are presented in the respective Jupyter notebooks or Python scripts for each algorithm.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to your needs.
