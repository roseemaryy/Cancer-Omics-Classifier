🧬 Cancer Omics Classification Project

📌 Overview

This project applies Machine Learning and Deep Learning to gene expression (omics) data to classify samples as Cancer or Normal.
The workflow covers the full end-to-end ML lifecycle: data preprocessing, model training, evaluation, and interpretation.

The goal is to demonstrate how AI can support healthcare by identifying patterns in omics data that may help with early cancer detection.

⸻

⚙️ Tech Stack
	•	Python (Pandas, NumPy, Matplotlib, Seaborn)
	•	Scikit-learn (Logistic Regression, Random Forest, preprocessing)
	•	TensorFlow/Keras (Deep Learning model)
	•	Joblib (for saving ML models)

⸻

🚀 Workflow
	1.	Data Preprocessing
	•	Loaded gene expression features (data.csv) and labels (labels.csv).
	•	Removed non-numeric columns (e.g., sample IDs).
	•	Standardized (scaled) features for better ML performance.
	•	Encoded labels (Cancer / Normal → 0/1).
	2.	Models Trained
	•	Logistic Regression → baseline classifier.
	•	Random Forest → ensemble ML model for higher performance.
	•	Neural Network (Keras) → deep learning approach with dropout layers to reduce overfitting.
	3.	Evaluation
	•	Accuracy, Precision, Recall, and F1-Score.
	•	Confusion Matrix for classification errors.
	•	Feature importance from Random Forest (top predictive genes).
	📊 Insights
	•	Certain genes showed significantly higher predictive power for cancer detection.
	•	Random Forest offered a balance of accuracy and interpretability.
	•	Deep Learning achieved the highest accuracy but requires more data/hyperparameter tuning.

⸻

💾 Saved Models
	•	cancer_logreg.pkl → Logistic Regression
	•	cancer_rf_model.pkl → Random Forest
	•	cancer_nn_model.keras → Neural Network

These models can be reloaded for further training, evaluation, or deployment.
👩‍💻 Author

Nyambura Kamau
AI/ML Engineer | Machine Learning Engineer | MLOps & Cloud
LinkedIn | GitHub

