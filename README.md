# Company Bankruptcy Prediction

This repository contains a **machine learning project** that predicts whether a company will go bankrupt within the next 1–2 years based on financial ratios.

The main work is implemented in the Jupyter Notebook:

* `Company_bankruptcy_prediction.ipynb`

The data comes from the following source:
https://www.kaggle.com/datasets/stealthtechnologies/predict-bankruptcy-in-poland

---

## Project Overview

The goal of this project is to build and compare several machine learning models to classify companies as **bankrupt** or **non-bankrupt**.

Key steps in the notebook include:

* Exploratory Data Analysis (EDA)
* Data cleaning and quality checks
* Handling missing values
* Dealing with class imbalance
* Feature scaling and preprocessing using pipelines
* Training and evaluating multiple models

---

## Dataset

The dataset consists of multiple yearly financial records (1stYear–5thYear). For this project:

* Only companies with a **1–2 year bankruptcy horizon** are selected
* Data from later years is used to align with the prediction objective
* The target variable is `class` (bankrupt vs. non-bankrupt)

---

## Models Used

The following models are trained and compared:

* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)

Techniques such as **class weighting**, **SMOTE**, and **threshold tuning** are used to address class imbalance.

---

## Requirements

To run the notebook, you will need:

* Python 3.x
* Common data science libraries such as:

  * numpy
  * pandas
  * matplotlib / seaborn
  * scikit-learn
  * imbalanced-learn

If you encounter missing libraries, install them using `pip install <library-name>`.

---

## How to Run

1. Clone the repository or download the files: `git clone https://github.com/krzysztofpk14/Bankrupcy-Prediction.git`
2. Open `Company_bankruptcy_prediction.ipynb` in Jupyter Notebook or Jupyter Lab
3. Run the cells from top to bottom

---

## Results

The notebook concludes with a comparison of all trained models and identifies the **best-performing model** based on evaluation metrics such as precision, recall, and F1-score.

---

# Authors
* Wiktor Kapica
* Krzysztof Kuba
