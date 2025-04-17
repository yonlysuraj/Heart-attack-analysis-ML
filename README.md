# Heart Attack Analysis - Machine Learning Project

This repository contains a comprehensive machine learning pipeline designed to analyze cardiovascular health indicators and predict the likelihood of a heart attack. The dataset includes key medical attributes such as age, cholesterol levels, resting blood pressure, and more, enabling data-driven insights into heart disease risk.

---

## 📁 Project Structure

```
Heart-attack-analysis-ML/
├── data/
│   └── heart.csv
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 🧰 Tech Stack

- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Data visualization
- **Scikit-learn (sklearn)** – Machine learning algorithms

---

## 📊 Dataset Overview

The dataset (`heart.csv`) is located in the `/data` directory and comprises multiple clinical features including:

- Age
- Sex
- Resting Blood Pressure (`trestbps`)
- Cholesterol (`chol`)
- Fasting Blood Sugar (`fbs`)
- Resting ECG Results (`restecg`)
- Maximum Heart Rate Achieved (`thalach`)
- Exercise-induced Angina (`exang`)
- ST Depression (`oldpeak`)
- Target (presence of heart disease)

---

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Heart-attack-analysis-ML.git
   cd Heart-attack-analysis-ML
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

---

## 📌 Objectives

- Conduct **exploratory data analysis (EDA)** to uncover patterns
- Handle missing values and outliers
- Apply data preprocessing techniques
- Train predictive models using:
  - Logistic Regression
  - Decision Tree Classifier
  - K-Nearest Neighbors
- Evaluate performance using metrics such as accuracy, precision, recall, and confusion matrix

---

## 📉 Visualizations

Key visualizations include:
- Correlation heatmaps
- Target distribution plots
- Pair plots for feature interaction
- Model evaluation metrics and confusion matrix

---

## ✍️ Author

**Suraj Mallick**  
Cloud Engineer | Machine Learning Enthusiast

---

## 📌 Disclaimer

This project is for academic and research purposes. The dataset is used for illustrative analysis and should not be treated as a substitute for clinical diagnosis or medical advice.

---
