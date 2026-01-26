A XgBoost based Cricket Score Predictor
# Cricket Score Predictor

A machine learning system that predicts T20 cricket match scores in real-time based on current match conditions (overs, wickets, venue, opposition).

Built to demonstrate end-to-end ML deployment: from data preprocessing to a production-ready Flask API with an interactive web interface.

---

##  Problem Statement

T20 cricket is fast-paced and unpredictable. Fans, analysts, and broadcasters need instant score projections to understand match momentum. This system predicts the final innings score using only the current match state.

---

##  Features

- **Real-time Predictions**: Enter current match stats (runs, wickets, overs) and get instant projections
- **Multi-factor Analysis**: Considers batting team, bowling team, venue, and match situation
- **Interactive UI**: Clean web interface built with HTML/CSS for easy testing
- **REST API Ready**: Flask backend can be integrated into mobile apps or dashboards
- **Model Serialization**: Pre-trained model stored as `.pkl` for fast inference

---

##  Tech Stack

- **ML/Data**: Python, Scikit-learn, Pandas, NumPy
- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript
- **Deployment**: Can be deployed on Heroku, AWS, or any Python-compatible host

---

##  Model Details

- **Algorithm**: [Specify: Random Forest / XGBoost / Linear Regression / etc.]
- **Dataset**: Historical T20 match data (2016-2024)
- **Features**: Batting team, bowling team, city/venue, current score, overs completed, wickets fallen
- **Target**: Final innings score
- **Accuracy**: [Add metrics: MAE ±15 runs, R² = 0.85, etc.]

---

Dataset: https://www.kaggle.com/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s

