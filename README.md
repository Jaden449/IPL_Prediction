<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>IPL Match Winner Prediction</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        h1, h2, h3 {
            color: #007acc;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li::before {
            content: "\2714\FE0F"; /* Checkmark */
            margin-right: 10px;
            color: green;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 5px;
            border-radius: 5px;
        }
        pre {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>🏏 IPL Match Winner Prediction</h1>
    
    <h2>📌 Overview</h2>
    <p>Predict the outcome of an Indian Premier League (IPL) match using machine learning and data analysis. This project processes historical IPL match data, extracts key features, and applies ML models to predict match results based on various in-game parameters.</p>
    
    <h2>✨ Features</h2>
    <ul>
        <li>Data Preprocessing & Feature Engineering from IPL datasets</li>
        <li>Handling Missing Values and normalizing team names for consistency</li>
        <li>Crucial Match Metrics Calculation (e.g., CRR, RRR, wickets left, balls left, etc.)</li>
        <li>Machine Learning Models Applied: Logistic Regression & Random Forest Classifier</li>
        <li>Performance Evaluation using accuracy scores and probability predictions</li>
        <li>Interactive Match Progression Analysis for insights</li>
    </ul>
    
    <h2>📊 Dataset</h2>
    <ul>
        <li>Match details: Teams, location, winner, scores, etc.</li>
        <li>Ball-by-ball delivery data</li>
    </ul>
    
    <h2>⚙️ Model Implementation</h2>
    
    <h3>🔹 Preprocessing</h3>
    <ul>
        <li>Encoding categorical features (teams, venues)</li>
        <li>Handling missing data</li>
    </ul>
    
    <h3>🔹 Feature Selection</h3>
    <ul>
        <li>Runs left, balls left, wickets, total runs, CRR, RRR</li>
    </ul>
    
    <h3>🔹 Training</h3>
    <p>🎯 Logistic Regression model using <code>sklearn.pipeline</code> for data transformation and classification</p>
    
    <h3>🔹 Evaluation</h3>
    <p>📊 Achieves ~80% accuracy in predicting match outcomes</p>
    
    <h3>🔹 Probability Prediction</h3>
    <p>🔢 Determines winning probability at different match stages</p>
    
    <h2>🚀 How to Use</h2>
    <pre>
1️⃣ Clone the repository:
    git clone https://github.com/your-repo/IPL-Match-Prediction.git
    cd IPL-Match-Prediction

2️⃣ Install dependencies:
    pip install -r requirements.txt

3️⃣ Run the model:
    python predict.py
    </pre>
    
    <h2>📌 Future Enhancements</h2>
    <ul>
        <li>Incorporate Deep Learning models for enhanced accuracy</li>
        <li>Add real-time match prediction API</li>
        <li>Improve visualizations with interactive dashboards</li>
    </ul>
    
    <h2>🤝 Contributing</h2>
    <p>Pull requests are welcome! Feel free to fork the repository and submit your improvements.</p>
    
    <h2>🚀 Happy Predicting! 🏏</h2>
</body>
</html>
