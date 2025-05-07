🚗 Crash Severity Prediction
This project explores predictive modeling techniques to classify crash severity—specifically identifying fatal vs. non-fatal crashes—using two machine learning approaches: Naive Bayes and Decision Tree classifiers. The goal is to support data-driven improvements in road safety and resource allocation.

📊 Project Overview
Objective: Predict whether a crash is fatal or non-fatal based on historical crash data.

Models Used:

Naive Bayes Classifier

Decision Tree Classifier

Key Focus: Handling class imbalance, maximizing recall on fatal crashes, and enabling real-world application in traffic safety planning.

⚙️ Features
Confusion matrix evaluation: accuracy, precision, recall

Cross-validation to avoid overfitting and improve model robustness

Class balancing strategies to address skewed fatality data

Interpretability of decision rules from the decision tree

Business insights: Linking predictions to actionable safety measures

📁 Contents
notebooks/ – Jupyter notebooks for model training, evaluation, and visualization

visualizations/ – Graphs and charts of decision trees and performance metrics

🔍 Future Improvements
Integrate more granular data (e.g., weather, time of day, vehicle types)

Experiment with ensemble models (Random Forests, Gradient Boosting)

Simulate policy changes using model predictions to estimate potential lives saved

📌 Getting Started
Clone this repo:

bash
Copy
Edit
git clone https://github.com/yourusername/crash-severity-prediction.git
cd crash-severity-prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebooks or scripts to train and evaluate models.
