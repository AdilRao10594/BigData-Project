Heart Disease Classification Using Decision and Regression Trees

📌 Project Overview:
Heart disease is a leading cause of mortality worldwide, making early detection crucial for effective treatment.
In this project, we leverage Big Data techniques to classify heart disease using Decision Tree and Regression Tree models. 
Our goal is to determine which model performs best in terms of accuracy, recall, and other key metrics.

📊 Dataset:

We used the Heart Disease Dataset from Kaggle:
🔗 Dataset Link

The dataset includes various patient attributes such as age, cholesterol levels, blood pressure,
and exercise-induced angina, which are used as input features for classification.

🔬 Methodology:

1. Data Preprocessing
Dropped irrelevant columns (e.g., sex, cp, slope) to improve model performance.
Handled missing values and normalized data where necessary.

2. Model Implementation:
Decision Tree Models: Three models with different train-test split ratios (65-35, 70-30, 80-20).
Regression Tree Models: Three models with the same train-test split ratios for comparison.

3. Evaluation Metrics:
Accuracy (Overall correctness of predictions)
Sensitivity/Recall (Ability to correctly classify heart disease cases)
Specificity (Ability to correctly identify healthy patients)
Precision (Proportion of correct positive predictions)
False Positive Rate (Misclassification of healthy patients as having heart disease)

🔎 Key Findings:
✅ Decision Tree Model (80-20 split) outperformed all other models, achieving:
86.49% Accuracy (Highest among all models)
85% Sensitivity (Detecting most heart disease cases)
88.24% Specificity (Minimizing false positives)
89.47% Precision (Reliable positive predictions)
✅ Regression Tree models showed lower performance, with accuracy ranging between 74.75% and 79.83%.
✅ Conclusion: The Decision Tree Model (80-20 split) is the best model for heart disease classification, balancing sensitivity and specificity, making it a reliable choice for healthcare applications.

🛠️ Technologies Used:
Python (pandas, NumPy, scikit-learn)
Jupyter Notebook
Big Data Techniques for Model Training and Optimization


🚀 Future Work:

🔹 Implement Random Forest or XGBoost for potentially better performance.
🔹 Deploy the model as a web-based application for real-time predictions.
🔹 Use a larger and more diverse dataset for improved generalization.
