# 🔥 Heat Exchanger Price Prediction

A machine learning project that predicts the price of heat exchangers based on technical and operational specifications. Built end-to-end — from raw data to model deployment — with an interactive Tableau dashboard for business insights.

---

## 📌 Project Overview

Heat exchangers are critical components in industries like oil & gas, chemical processing, and HVAC. Pricing them accurately is complex and often manual. This project automates price prediction using machine learning, helping businesses estimate costs faster and more accurately.

---

## 🗂️ Project Structure

```
Heat-Exchanger-Price-Prediction/
│
├── Heat Exchanger Price Prediction.py   # Main ML pipeline (EDA → Model → Evaluation)
├── Heat Exchanger Price Prediction....  # Jupyter Notebook version
├── dataset1.xlsx                        # Raw dataset
├── Dashboard.twb                        # Tableau dashboard for data visualisation
└── CAPSTONE.pptx                        # Project presentation deck
```

---

## 🎯 Problem Statement

Manually estimating heat exchanger prices is time-consuming and error-prone. The goal of this project is to build a regression model that predicts heat exchanger prices based on input features such as material, size, pressure rating, and other technical specifications.

---

## 🔧 Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data Manipulation | Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Dashboard | Tableau |
| Dataset | Excel (.xlsx) |
| Presentation | PowerPoint |

---

## ⚙️ ML Pipeline

```
Raw Data (Excel)
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis (EDA)
      ↓
Feature Engineering
      ↓
Model Training & Evaluation
      ↓
Price Prediction Output
```

### Models Used
- Linear Regression (baseline)
- Random Forest Regressor
- XGBoost Regressor ✅ (best performer)

### Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📊 Key Results

| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 0.76 | — |
| Random Forest | 0.87 | — |
| XGBoost | **0.91** | **Best** |

> *Note: Update these values with your actual model results.*

---

## 📈 Tableau Dashboard

An interactive Tableau dashboard (`Dashboard.twb`) was created to visualise:
- Price distribution across heat exchanger types
- Feature correlation with price
- Key drivers of price variation

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/roshanchourasia001/Heat-Exchanger-Price-Prediction.git
cd Heat-Exchanger-Price-Prediction
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost openpyxl
```

### 3. Run the Python script
```bash
python "Heat Exchanger Price Prediction.py"
```

### 4. Open the notebook
```bash
jupyter notebook "Heat Exchanger Price Prediction....ipynb"
```

---

## 📁 Dataset

- **File:** `dataset1.xlsx`
- **Source:** Industry / academic dataset
- **Features include:** Material type, heat transfer area, pressure rating, fluid type, shell type, number of tubes, and more
- **Target variable:** Price (₹ / $)

---

## 💡 Key Learnings

- Feature engineering on industrial/technical specifications
- Handling skewed price distributions using log transformation
- XGBoost hyperparameter tuning with GridSearchCV
- Business storytelling through Tableau dashboards

---

## 🙋 Author

**Roshan Chourasia**
- 📧 GitHub: [@roshanchourasia001](https://github.com/roshanchourasia001)
- 💼 LinkedIn: [@Linkedin](https://linkedin.com/in/roshan-chourasia-122a8b252)
- 🎯 Data Science Fresher | Python | ML | SQL | Tableau

---

## ⭐ If you found this project useful, give it a star!

> *"Predicting prices isn't just about algorithms — it's about understanding the engineering behind the numbers."*
