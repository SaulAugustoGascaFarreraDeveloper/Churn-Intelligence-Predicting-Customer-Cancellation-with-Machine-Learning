# Churn-Intelligence-Predicting-Customer-Cancellation-with-Machine-Learning
Machine Learning model to forecast customer subscription cancellation (Churn)

📡 Telecom Customer Churn Prediction

Machine Learning model to forecast customer subscription cancellation (Churn)

📌 Business Problem

  Interconnect, a telecommunications operator, wants to predict customer churn in advance.
  
  If a customer is likely to cancel their subscription, the company can proactively offer:
  
  Promotional codes
  
  Special pricing plans
  
  Retention campaigns

The objective is to reduce churn rate and increase customer lifetime value (CLV).

🏢 Company Services

Interconnect provides two primary services:

📞 Landline Communication

🌐 Internet Services

Additional services include:

  🛡️ DeviceProtection (Antivirus Software)
  
  🔐 OnlineSecurity (Malicious website blocker)
  
  🧑‍💻 TechSupport
  
  ☁️ OnlineBackup (Cloud storage & backup)
  
  📺 StreamingTV
  
  🎬 StreamingMovies

Customers can:

  Pay monthly or sign 1–2 year contracts
  
  Use multiple payment methods
  
  Receive electronic billing

🎯 Project Objective

  Develop and compare multiple Machine Learning classification models to predict whether a customer will cancel their subscription.
  
  The final model helps the marketing team identify high-risk customers before churn happens.

📊 Machine Learning Approach

  This project includes:
  
  Data preprocessing and feature engineering
  
  Handling categorical variables
  
  Model training and evaluation
  
  Comparison of multiple classification algorithms
  
  Models tested may include:
  
  Logistic Regression
  
  Random Forest
  
  Gradient Boosting
  
  Other ensemble methods

📈 Evaluation Metrics
🥇 Primary Metric: AUC-ROC

  The main evaluation metric is AUC-ROC (Area Under the Receiver Operating Characteristic Curve).

Why AUC-ROC?

  Measures model performance in binary classification
  
  Evaluates how well the model distinguishes between churn and non-churn customers
  
  Robust against class imbalance

📌 Secondary Metric: Accuracy

  Accuracy is also evaluated to measure overall prediction correctness.

📎 Results

Final model performance (from Jupyter Notebook results):

<img width="1299" height="580" alt="image" src="https://github.com/user-attachments/assets/6fb89186-7df1-49fd-a984-fc55468955a6" />


(Replace with your actual values)

🧠 Business Impact

  With this model, the company can:
  
  Reduce churn rate
  
  Increase retention
  
  Improve targeted marketing campaigns
  
  Optimize promotional budget allocation

🛠️ Tech Stack

  Python

  Pandas
  
  NumPy
  
  Scikit-learn
  
  Matplotlib / Seaborn
  
  Jupyter Notebook

🚀 Future Improvements

  Hyperparameter tuning with GridSearch / Optuna
  
  Cost-sensitive learning
  
  SHAP for model explainability
  
  Deployment as REST API
  
  Integration into CRM systems
