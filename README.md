# AI Social Media Usage Analysis System 📱

An intelligent dashboard to analyze screen time, detect addiction risk, understand productivity impact, and predict user behaviour using Machine Learning.

This repository features both a standalone premium HTML dashboard (powered by Chart.js) and an interactive Streamlit Machine Learning web application.

---

## 🌟 Features

### 1. Standalone HTML/CSS/JS Dashboard
- An interactive, modern, and beautiful dashboard interface.
- Rich interactive charts powered by **Chart.js**.
- Key metrics visualization: average screen time, average sleep hours, productivity score, and addiction level breakdown.

### 2. Streamlit ML Web Application
- **Live Addiction Risk Predictor**: Enter your demographic and usage patterns (age, daily hours, sessions, sleep hours, notifications) to get a real-time risk assessment and percentage score.
- **Personalized Recommendations**: Receive dynamically generated advice on how to improve digital well-being (e.g. sleep guidance, notification settings).
- **ML Models Comparison**: Train, test, and evaluate three algorithms on-the-fly:
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - Logistic Regression
- **Performance Evaluation**: Real-time display of cross-validation accuracy, feature importances, ROC curves, and confusion matrices.
- **Sentiment & Emotional Analysis**: Uses **TextBlob** to classify simulated user posts and analyze emotional sentiments by platform.

---

## 📁 Project Structure

```text
├── social-media-dashboard.html  # Standalone interactive dashboard (HTML/JS/Chart.js)
├── socialmedia.py               # Streamlit application containing the ML models & dashboard
├── app.py                       # Copy of socialmedia.py (standard Streamlit entrypoint)
├── requirements.txt             # Python packages required to run the application
├── .gitignore                   # Files and directories ignored by Git
└── README.md                    # This project documentation
```

---

## 🚀 Getting Started

### 📋 Prerequisites

Make sure you have Python 3.8+ installed on your computer.

### ⚙️ Installation & Running the Dashboard

1. **Clone the repository:**
   ```bash
   git clone https://github.com/tejas1901/socialmedia-analysis.git
   cd socialmedia-analysis
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

---

## 📦 Python Dependencies

The system leverages the following Python libraries:
- `streamlit` - App framework
- `pandas` & `numpy` - Data manipulation
- `matplotlib` & `seaborn` - Static plotting
- `plotly` - Interactive plotting
- `scikit-learn` - Machine Learning modelling and evaluation
- `textblob` - Sentiment analysis

---

## ☁️ Streamlit Community Cloud Deployment

To host this interactive Social Media Dashboard online:
1. Log in to [Streamlit Community Cloud](https://share.streamlit.io/).
2. Click **Create app** and connect your GitHub account.
3. Select this repository (`socialmedia-analysis`), branch (`main`), and set the main file path to `app.py`.
4. Click **Deploy!**
