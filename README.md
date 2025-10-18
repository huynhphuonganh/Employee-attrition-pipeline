# Employee-attrition-pipeline
🧩 Problem Statement

The current workforce situation at IBM shows an increasing employee attrition rate, impacting overall productivity and recruitment costs. Early identification of employees at high risk of leaving allows the company to proactively implement retention strategies and optimize workforce planning.

💡 Introduction

This project analyzes and predicts employee attrition at IBM using a dataset of 1,471 records and 35 features, combining data visualization and machine learning to support strategic HR decision-making.

🎯 Objective

Monitor overall workforce trends and identify departments or job roles with high attrition risk.

Predict employees with a high probability of leaving and uncover their key characteristics.

⚙️ Approach

Visualization: Built a Tableau Dashboard to track attrition trends by department, job role, gender, age group, salary, and more.

Preprocessing: Checked and handled multicollinearity using VIF (Variance Inflation Factor) to ensure model stability and interpretability.

Modeling: Applied multiple classification algorithms — Logistic Regression, Decision Tree, Random Forest, and XGBoost — and selected Random Forest as the best-performing model.

Model Evaluation: Implemented 5-Fold Cross Validation to assess model generalization.

Performance: Achieved an average AUC = 0.98 (Random Forest). Employees with Attrition_Probability > 0.6% were classified as high-risk.

📊 Results & Suggested Actions

Identified 4 employees at high risk of leaving, characterized by factors such as overtime workload, low salary, and shorter tenure.

Proposed targeted retention actions, including improving compensation, reducing overtime, and offering career development opportunities to enhance employee engagement and reduce attrition.
