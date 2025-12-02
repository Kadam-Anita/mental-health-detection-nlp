#Mental Health Prediction Model

A machine learning project that predicts a person's mental state based on lifestyle patterns like screen time, sleep, social media usage, stress, anxiety, and more. This model also helps you understand which factors affect mental health the most using SHAP explainability.

🔥 What this project does
-- Predicts if a person is Healthy, At_Risk, or Stressed
-- Shows which lifestyle habits strongly impact mental health
-- Visualizes model explanations using SHAP
-- Works for new incoming data
-- Gives 80%+ accuracy (XGBoost)

🛠️ Model Used
-- XGBoost Classifier

🚀 Steps in the Project
-- Load and clean the data
-- Encode text columns
-- Split into train/test
-- Train the XGBoost model
-- Evaluate using accuracy + confusion matrix
-- Explain results using SHAP
-- Save the final model using joblib

📊 Model Accuracy
The model gives around 80–90% accuracy, depending on the dataset split.

📝 Example Prediction
  Predicted Class: Stressed  
  Probabilities:
  Healthy:   0.005%
  At_Risk:   0.004%
  Stressed:  99.99%

🎯 What Insights You Get
-- Sleep hours help improve mental state
-- High screen time increases risk
-- High anxiety & stress levels strongly predict "Stressed"
-- Positive interactions improve mood
-- Physical activity has a positive impact




Predict new data
