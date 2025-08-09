# 💵Loan Approval Prediction Using Machine Learning
## 📌 Project Objective

The main objective of this project is to create a machine learning-based system capable of predicting whether a loan application should be approved or rejected based on the applicant’s financial, credit, and personal details. The system is designed to:

- Automate and accelerate loan decision-making.
- Reduce manual processing errors.
- Identify and filter out high-risk applicants effectively.
- Improve approval accuracy using data-driven insights.
- Support banks and financial institutions in making consistent and fair lending decisions.

## 📊 Key Insights from Analysis
- Applicants with CIBIL Scores above ~700 have a significantly higher approval rate compared to those with lower scores.
- Higher annual income generally increases the chances of approval, especially when the requested loan amount is proportionate to the income.
- The loan-to-income ratio is a key metric — lower ratios strongly correlate with approvals.
- Debt-to-Income ratios are consistently lower in approved applications, indicating healthier financial standing.
- Applicants with greater asset values (Residential, Commercial, Bank) enjoy higher approval likelihood.
- Having more dependents slightly decreases the approval probability.
- Loan terms between 8–12 months are associated with a better approval rate.
- Loan Amount and Income show a high positive correlation, and CIBIL Score is strongly correlated with Loan Status.
- Cluster patterns reveal that approved and rejected applications fall into distinct financial and credit categories.
- Higher quartiles in asset value distributions align with better approval chances.

## 📈 Key Performance Indicators (KPIs)
- The Ensemble Voting Classifier achieved the highest accuracy of 98.44%, making it the most reliable model for prediction.
- The Random Forest Classifier delivered a strong performance with 97.74% accuracy, closely followed by the Decision Tree Classifier at 97.66%.
- The Support Vector Machine (SVM) had significantly lower performance with 63.23% accuracy, indicating it is less suitable for this dataset.
- The overall loan approval rate in the dataset stands at approximately 60%.
- The average CIBIL score for approved applicants is around 750, considerably higher than for rejected applicants.
- Approved applicants maintain a lower loan-to-income ratio (~2.5) compared to rejected applicants (~5.0).
- The debt-to-income ratio is significantly lower for approved cases, showing the importance of manageable financial obligations.
- The most influential predictors in loan approval decisions are CIBIL Score, Annual Income, Loan Amount, and Asset Values (Residential, Commercial, and Bank).

 ## 🛠️ Models & Performance
- Decision Tree Classifier → Accuracy: 97.66%
- Support Vector Machine (SVM) → Accuracy: 63.23%
- Random Forest Classifier → Accuracy: 97.74%
- Ensemble Voting Classifier → Accuracy: 98.44% ✅ (Best Performer)

## 📌 Additional Highlights
- Data Preprocessing: Missing values were replaced using column means, and outliers were capped using the IQR method.
- Feature Engineering: New features like Loan-to-Income Ratio, Debt-to-Income Ratio, and Asset Quartiles were created.

EDA included:

- Distribution plots for all numerical variables.
- Boxplots and scatterplots for trend identification.
- Correlation heatmaps to understand relationships.
- Quartile-based asset analysis for deeper insights.
- Advanced visuals like 3D plots, radar charts, and parallel coordinate plots.

Model Comparison: Direct accuracy evaluation was performed to select the best-performing model.

## 🚀 Conclusion
The Ensemble Model delivers exceptional performance with 98.44% accuracy, making it the most reliable choice for predicting loan approvals. Key drivers like CIBIL Score, Loan-to-Income Ratio, and Asset Values have a substantial impact on decision-making. This model can be effectively deployed in banking systems to enable faster, more consistent, and highly accurate loan approvals.
