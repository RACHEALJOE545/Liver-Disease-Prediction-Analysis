# Liver-Disease-Prediction-Analysis Using Linear Regression

<img width="740" height="516" alt="Screenshot 2025-10-18 121904" src="https://github.com/user-attachments/assets/841ec307-8ccb-47c4-9652-04f80bb8fe6f" />



## 📘 Introduction:

This project explores liver health prediction using machine learning, focusing on the detection and analysis of liver disease risk factors.
The motivation behind this work is the growing prevalence of liver-related illnesses and the challenge of diagnosing them early through non-invasive means. By assessing clinical parameters such as enzyme levels and protein concentrations, the model aims to help healthcare professionals predict potential liver dysfunctions before severe symptoms appear.

The analysis leverages exploratory data analysis (EDA) and supervised learning techniques to uncover relationships between medical features and bilirubin concentration, a major biomarker for liver disease.


## 📊 Key Metrics:

-What is the average and range of Total Bilirubin levels across the dataset?

-How do Direct Bilirubin, ALT, and AST correlate with Total Bilirubin?

-Which enzymatic features (ALP, ALT, AST) show the strongest predictive influence?

-How does Albumin and Total Protein level variation relate to liver disease presence?

-What is the model’s accuracy, precision, recall, and F1-score in predicting disease presence?

-Which features contribute most to the predictive model’s outcome?


## 🧠 Skills and Concepts Demonstrated:

- Exploratory Data Analysis (EDA) using pandas, matplotlib, and seaborn

- Feature Engineering and Correlation Analysis for biomarker relationships

- Machine Learning Model Development with scikit-learn (sklearn)

- Regression and Classification Techniques (e.g., Logistic Regression, Decision Trees)

- Model Evaluation Metrics – accuracy, confusion matrix, precision, recall, F1-score

- Data Cleaning and Normalization to improve model performance

- Visualization of Medical Data Trends and predictor importance
  

## Data Visualization:

<img width="822" height="657" alt="Screenshot 2025-10-18 124911" src="https://github.com/user-attachments/assets/f6940fad-381b-4cd9-a894-cd9b7b759aa0" />


## 📈 Analysis Interpretation: 

- Direct Bilirubin shows the strongest correlation with Total Bilirubin, as expected from its biochemical relationship.

- Enzymatic markers like ALT, AST, and ALP exhibit positive correlation with bilirubin levels — elevated values indicate       liver cell damage or reduced excretory function.

- Albumin and Total Proteins show moderate to weak correlation, reflecting liver synthesis capacity.

- Machine learning models demonstrated a predictive capability, identifying patients with potential liver dysfunction with     moderate accuracy (around 50–60%, depending on the model).

- Visualizations reveal distinct separation patterns between healthy and unhealthy patients based on enzyme and bilirubin      distributions.


## You can interact with the notebook here:
https://colab.research.google.com/drive/1P4T2LCNiBqKJ4aTD5KCHOgigekXSMri2?usp=sharing
  

## 🧩 Conclusions:

- The study confirms that bilirubin and enzyme levels are significant indicators of liver health.

- Predictive modeling can provide early warnings for liver dysfunction using basic biochemical parameters.

- Further optimization with larger datasets and feature tuning could significantly improve accuracy and clinical usability.
  

## 💡 Recommendations:

- Collect more balanced datasets to address class imbalance in healthy vs. diseased samples.

- Experiment with ensemble models (Random Forest, XGBoost) to boost predictive power.

- Normalize and scale medical features for consistent model interpretation.

- Deploy the model via a simple interface (Flask or Streamlit) for clinical usability.

- Integrate additional health parameters such as BMI, age, alcohol use, and comorbidities for better predictive strength.
