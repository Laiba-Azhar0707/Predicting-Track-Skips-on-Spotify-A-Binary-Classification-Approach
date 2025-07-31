🎵 Predicting Track Skips on Spotify
A Binary Classification Project using Decision Tree

📌 Overview
This project focuses on building a binary classification model to predict whether a user will skip a track on Spotify. Using a real-world dataset, we explored listener behavior across multiple platforms and user contexts. The primary goal was to classify the target variable skipped using a Decision Tree Classifier.

🎯 Objective
To understand and model user interactions with music tracks on Spotify, identifying key factors that contribute to skips and improving recommendation logic.

🧩 Dataset
The dataset contains information on:

Platform used (iOS, Android, web, etc.)

Whether shuffle was enabled

Duration played

Reason for track start

Timestamps (converted to hour/day/weekend)

Whether a track was skipped (0 or 1)

Unnecessary features such as artist names and song titles were removed during preprocessing due to high cardinality and limited predictive value.

⚙️ Tools & Libraries
Python

Pandas, NumPy

scikit-learn

DecisionTreeClassifier

Matplotlib & Seaborn (for EDA)

🧠 Model
The model used was a Decision Tree Classifier. Performance was evaluated using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📊 Evaluation
While the model offers decent baseline performance, further improvements can be made by:

Trying other classifiers (Random Forest, XGBoost)

Hyperparameter tuning

Cross-validation

📁 Project Structure

├── data/
│   └── spotify_data.csv
├── notebooks/
│   └── analysis.ipynb
├── models/
│   └── decision_tree.pkl
├── README.md
└── requirements.txt
🚀 Future Work
Add feature importance visualization

Try ensemble methods for better performance

Deploy the model as a simple web app using Streamlit

✅ Status
Completed – Model trained and evaluated using Decision Tree(Accuracy = 0.95).
