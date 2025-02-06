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

## Visualization

<img width="793" alt="Screenshot 2025-02-05 at 10 40 56 PM" src="https://github.com/user-attachments/assets/88409545-2e7a-4e4d-bcfc-18553da00344" />

The correlation matrix highlights key insights into recidivism predictors. It shows a strong positive correlation between prior felony convictions and recidivism, emphasizing the importance of criminal history. The "Supervision Risk Score First" also strongly correlates with reoffending, indicating higher-risk individuals are more likely to recidivate. Interestingly, drug test results show a weak link to recidivism, while factors like program attendance and employment have a more significant influence on lowering reoffending likelihood.

<img width="434" alt="Screenshot 2025-02-05 at 10 41 17 PM" src="https://github.com/user-attachments/assets/9006152e-e0a9-4e3d-9907-7852d957d560" />

The density plot visualizes the distribution of THC-positive drug tests across different
age groups at the time of release. The majority of tests concentrate near zero across all age
groups, indicating that most individuals tested negative for THC. Younger age groups, such as
18-22 and 23-27, exhibit slightly broader distributions compared to older groups, suggesting a
marginally higher prevalence of THC-positive tests. However, the overall density diminishes
significantly as the THC-positive test rate increases, irrespective of age

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

