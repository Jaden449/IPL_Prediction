🏏 IPL Match Winner Prediction

📌 Overview

Predict the outcome of an Indian Premier League (IPL) match using machine learning and data analysis. This project processes historical IPL match data, extracts key features, and applies ML models to predict match results based on various in-game parameters.

✨ Features

✅ Data Preprocessing & Feature Engineering from IPL datasets✅ Handling Missing Values and normalizing team names for consistency✅ Crucial Match Metrics Calculation (e.g., Current Run Rate (CRR), Required Run Rate (RRR), wickets left, balls left, etc.)✅ Machine Learning Models Applied: Logistic Regression & Random Forest Classifier✅ Performance Evaluation using accuracy scores and probability predictions✅ Interactive Match Progression Analysis for insights

📊 Dataset

The project utilizes historical IPL match data from CSV files, including:
📌 Match details: Teams, location, winner, scores, etc.📌 Ball-by-ball delivery data

⚙️ Model Implementation

🔹 Preprocessing

🔹 Encoding categorical features (teams, venues)🔹 Handling missing data

🔹 Feature Selection

🏏 Runs left, balls left, wickets, total runs, CRR, RRR

🔹 Training

🎯 Logistic Regression model using sklearn.pipeline for data transformation and classification

🔹 Evaluation

📊 Achieves ~80% accuracy in predicting match outcomes

🔹 Probability Prediction

🔢 Determines winning probability at different match stages

🚀 How to Use

1️⃣ Clone the repository:

git clone https://github.com/your-repo/IPL-Match-Prediction.git
cd IPL-Match-Prediction

2️⃣ Install dependencies:

pip install -r requirements.txt

3️⃣ Run the model:

python predict.py

📌 Future Enhancements

🔹 Incorporate Deep Learning models for enhanced accuracy🔹 Add real-time match prediction API🔹 Improve visualizations with interactive dashboards

🤝 Contributing

Pull requests are welcome! Feel free to fork the repository and submit your improvements.

🚀 Happy Predicting! 🏏

