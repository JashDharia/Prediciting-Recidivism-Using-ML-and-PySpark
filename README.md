# Recidivism Prediction Project 📊⚖️

## Overview 🌟

Recidivism—the tendency for previously convicted individuals to reoffend after release—is a persistent issue in the criminal justice system. This project utilizes advanced **Machine Learning** techniques to predict the likelihood of an individual reoffending within **three years** of release, aiming to provide actionable insights for parole boards, correctional facilities, and policymakers.

### Objectives 🎯:
- **Prediction** 🔮: Estimate the likelihood of recidivism.
- **Inference** 🧐: Identify significant predictors of reoffending.
- **Operational Goals** 💡: Optimize resource allocation, support policy development, and improve rehabilitation efforts.

---

## Dataset Overview 🗃️

The dataset comprises records from a **criminal justice database** with over **25,000 instances** and **53 attributes** per record. These attributes span demographic, criminal history, and post-release factors, including:

- **Demographic Information**: Age, Gender, Race 👩‍⚖️
- **Criminal History**: Type of offenses, Previous convictions 🔒
- **Post-release Environment**: Employment status, Community support, Rehabilitation program participation 🌱

---

## Approach 🧑‍💻

### Data Preprocessing 🛠️:
- **Missing Values** ❓: Imputed or removed based on significance.
- **Feature Engineering** ⚙️: Categorical variables like Education Level and Supervision Risk Score were encoded using one-hot encoding.

### Key Features for Prediction 🔑:
- Age at Release, Gender, Race, Education Level 📅
- Prior Arrests (felony, violent, property, drug) 🚔
- Employment Status, Participation in Programs 🏢👥
- Prior Convictions, Supervision Risk Score 📈

---

## Models and Algorithms 🧠

- **Logistic Regression** 📊: Used for binary classification (reoffend or not).
- **Random Forest** 🌲: Implemented for handling non-linear relationships in data.
- **Gradient Boosting** 🌟: A robust model that improves upon weaker models.
- **XGBoost** 🚀: A highly effective gradient boosting model for fast and accurate predictions.

---

## Results and Performance 📈

- **Accuracy** 🎯: 85%
- **Precision** ⚖️: 83%
- **Recall** 🔍: 78%
- **F1-Score** 🏆: 80%

---

## Conclusion 🎉

The machine learning models have shown promising results in predicting recidivism, with an accuracy rate of **85%**. Key features such as **Age at Release**, **Prior Arrests**, and **Supervision Risk Score** have been identified as significant predictors. These insights can support more informed decisions in the criminal justice system, potentially improving rehabilitation efforts and reducing recidivism rates.

---

## Installation 🛠️

To get started with the project locally, clone the repository and install the dependencies:

```bash
git clone https://github.com/yourusername/recidivism-prediction.git
cd recidivism-prediction
pip install -r requirements.txt

