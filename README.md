Recidivism Prediction Project
Project Overview
Recidivism is a persistent challenge within the criminal justice system, referring to the tendency of individuals previously convicted of crimes to reoffend after their release. The goal of this project is to develop a predictive machine learning model that estimates the likelihood of reoffending within three years post-release. By analyzing historical data, including demographic information, past criminal records, behavior during incarceration, and post-release environment factors, the project aims to support parole boards and correctional facilities in assessing risk, tailoring interventions, and optimizing resource allocation.

Key Objectives:
Risk Assessment: Generate a risk score to assess the likelihood of recidivism, supporting parole decisions.
Tailored Interventions: Identify individuals who need more intensive rehabilitation or monitoring.
Resource Allocation: Prioritize resources to individuals at higher risk of reoffending.
Policy Development: Provide data-driven insights to inform criminal justice policies and rehabilitation strategies.
Project Goals
The project is structured around three main pillars:

1. Prediction:
Develop a predictive model to estimate the likelihood of recidivism.
Forecast reoffending based on various attributes such as criminal history, demographic factors, and rehabilitation program participation.
2. Inference:
Identify significant predictors of recidivism.
Quantify the impact of various factors, such as age, employment, education, and prior criminal behavior.
3. Other Goals:
Model Evaluation and Comparison: Compare different machine learning models (Random Forest, Logistic Regression, SVM, Gradient Boosting).
Resource Optimization: Use predictions to optimize resource allocation in correctional facilities.
Policy Support: Provide empirical data to support policy development and legislative changes.
Data Exploration and Visualizations
Dataset Overview:
The dataset comprises over 25,000 records with 53 attributes per record. It includes demographic data, criminal history, behavior during incarceration, and post-release environment factors.

Data Cleaning & Preprocessing:
Missing values were imputed or removed based on attribute significance.
Categorical variables were encoded using one-hot encoding.
Key Visualizations:
Positive Drug Test Distribution by Age Group: Density plot illustrating the THC-positive drug test results by age group at release.
Correlation Heatmap: Heatmap showing the relationship between recidivism and other factors such as employment, marital status, and previous offenses.
Recidivism by Employment Status: Boxplot comparing the employment percentage between individuals who recidivated and those who did not.
Racial Disparities in Recidivism Rates: Bar chart comparing recidivism rates across different racial groups.
Methodology
Features Used:
Age at release, gender, race, education level, supervision risk score, prior criminal offenses, employment status, program attendance, etc.
Models Implemented:
Logistic Regression: Baseline model with linear assumptions.
Random Forest: Ensemble method known for reducing variance and capturing complex patterns.
Support Vector Machine (SVM): Non-linear model with kernel functions, requiring extensive tuning.
Gradient Boosting (XGBoost): Effective in handling imbalanced data and capturing feature interactions.
Model Performance:
Logistic Regression: Accuracy = 72.1%
Random Forest: Accuracy = 73.5%
SVM: Accuracy = 72.1%
XGBoost: Accuracy = 74.6% (best-performing model)
Key Findings:
Prior felony convictions and supervision risk scores are strong predictors of recidivism.
Employment stability and participation in rehabilitation programs reduce the likelihood of reoffending.
There are racial disparities in recidivism rates, indicating potential systemic issues.
Results
Prediction Goals:
Random Forest and XGBoost models achieved the highest accuracy (73.5% and 74.6%, respectively).
The models can classify individuals into risk categories (low, medium, high) to support parole decisions.
Inference Goals:
Key predictors such as employment status, criminal history, and program attendance were identified as crucial factors for predicting recidivism.
Feature importance analysis helped prioritize risk assessment factors.
Final Model:
The project’s findings are suitable for real-world deployment, assisting in parole decisions and policy development. Efforts were made to ensure fair predictions by minimizing biases, with continuous monitoring recommended.

Challenges and Ethical Considerations
Data quality issues such as missing or inconsistent values required careful handling and imputation.
Addressing class imbalance through resampling methods was necessary to avoid model bias.
Ethical considerations, including mitigating biases and ensuring privacy, were integral to model development.
Conclusion
This project demonstrates the potential of machine learning techniques in predicting recidivism and improving criminal justice outcomes. The models provide valuable insights into the factors influencing reoffending and support more data-driven decisions for parole and rehabilitation.

How to Run the Code
Clone the repository:
git clone https://github.com/yourusername/recidivism-prediction.git
Install required libraries:
pip install -r requirements.txt
Run the Jupyter notebook or Python script to train models and analyze results.
