

# Diabetes Prediction

This project focuses on predicting the likelihood of diabetes in individuals using machine learning models. It involves data preprocessing, feature selection, and training various machine learning models to achieve accurate predictions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)

---

## Introduction
Diabetes is one of the most prevalent chronic diseases worldwide. Early diagnosis and intervention can reduce the risk of complications. This project uses machine learning algorithms to predict diabetes based on various health parameters.

---

## Features
- Data preprocessing and feature scaling
- Exploratory data analysis (EDA) and visualizations
- Multiple machine learning models implemented
- Model comparison and performance evaluation
- Flask-based web application for real-time predictions

---

## Technologies Used
This project is built using the following technologies:
- **Jupyter Notebook** (96.6% of the codebase)
- **Python** (1.9% of the codebase)
- **HTML** (1.5% of the codebase)

Python libraries used:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Flask

---

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/swapnilbilgoji/Diabetes_prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Diabetes_prediction
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Flask application:
   ```bash
   python app.py
   ```

6. Access the Flask application:
   Open a web browser and navigate to:
   ```
   https://{your_url}.pwskills.app:5000/
   ```

---

## Usage
1. Launch the Flask application using the above instructions.
2. Use the web interface to input health parameters such as glucose level, BMI, age, etc.
3. Get real-time predictions on whether the individual is likely to have diabetes.

---

## Dataset
The dataset used in this project contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **Blood Pressure**: Diastolic blood pressure (mm Hg)
- **Skin Thickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history
- **Age**: Age of the person
- **Outcome**: 1 if the individual has diabetes, 0 otherwise

The dataset can be found [here](https://www.kaggle.com/datasets).

---

## Model Details
The following machine learning models were implemented and evaluated:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Gradient Boosting**

The models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

---

## Results
The performance of the machine learning models is summarized below:

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| Logistic Regression    | 78.5%   | 76.0%     | 80.2%  | 78.1%    |
| Decision Tree          | 75.3%   | 72.5%     | 77.8%  | 75.0%    |
| Random Forest          | 82.1%   | 80.5%     | 83.0%  | 81.7%    |
| Support Vector Machine | 80.2%   | 78.3%     | 81.6%  | 79.9%    |
| Gradient Boosting      | 84.0%   | 82.7%     | 85.2%  | 83.9%    |

**Best Model**: Gradient Boosting achieved the highest accuracy and F1 Score, making it the most reliable model for predicting diabetes in this project.

---

## Contributors
- [Swapnil Bilgoji](https://github.com/swapnilbilgoji)

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements
- The dataset is provided by [Kaggle](https://www.kaggle.com).
- Thanks to the open-source community for the libraries used in this project.

---
