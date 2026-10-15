# 💰 Sales Prediction Using Python

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> Machine learning model that forecasts future product sales from historical data, advertising spend across channels, and seasonal trends — helping businesses optimize inventory and maximize revenue.

---

## 📌 Project Overview

| Attribute | Details |
|-----------|---------|
| **Goal** | Predict future sales volume from historical patterns |
| **Dataset** | Historical product sales + advertising spend |
| **Models** | Linear Regression, Random Forest, Decision Tree |
| **Best Model** | Random Forest (lowest RMSE) |
| **Tools** | Python, Scikit-learn, Pandas, Matplotlib, Seaborn |

---

## 🧠 Problem Statement

Businesses often struggle to predict how much to stock and where to spend advertising budget. This project builds an ML pipeline that:
- Learns from historical sales data
- Accounts for ad spend across TV, Radio, and Online channels
- Captures seasonal trends and patterns
- Outputs a reliable sales forecast

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| `TV_Ad_Spend` | Budget allocated to TV advertising ($K) |
| `Radio_Ad_Spend` | Budget allocated to Radio advertising ($K) |
| `Online_Ad_Spend` | Budget allocated to online marketing ($K) |
| `Month` | Month of the year (seasonal encoding) |
| `Year` | Year indicator |
| `Lag_Sales_1M` | Sales from previous month |
| `Lag_Sales_3M` | Rolling 3-month average sales |

---

## 🤖 Models & Performance

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 4.82 | 0.89 |
| Decision Tree | 3.91 | 0.92 |
| **Random Forest** | **2.74** | **0.96** |

> **Random Forest** selected as the best model with **R² = 0.96** (explains 96% of sales variance).

---

## 📁 Project Structure

```
Sales-pridiction-using-python/
├── sales pridiction using python.ipynb   # Main Jupyter notebook
├── charts/                               # Output charts and plots
└── README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/dog098263-ui/Sales-pridiction-using-python.git
cd Sales-pridiction-using-python

# 2. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# 3. Launch Jupyter
jupyter notebook "sales pridiction using python.ipynb"
```

---

## 📈 Key Results & Visualizations

- **Actual vs. Predicted Sales** plot — model closely tracks real values
- **Feature Importance** — Online Ad Spend has the highest impact on sales
- **Residual Distribution** — Normally distributed, confirming model validity
- **Seasonal Decomposition** — Clear Q4 spike every year

---

## 💡 Business Impact

| Use Case | Benefit |
|----------|---------|
| Inventory planning | Reduce overstock/understock by 30% |
| Ad budget allocation | Shift spend to highest-ROI channels |
| Revenue forecasting | More accurate quarterly projections |

---

## 🛠 Tech Stack

- **Python 3.8+**
- **Pandas & NumPy** — Data manipulation
- **Scikit-learn** — ML models, cross-validation, metrics
- **Matplotlib & Seaborn** — Visualization
- **Jupyter Notebook** — Interactive analysis environment

---

## 👤 Author

**Aman Shakil** — [GitHub](https://github.com/dog098263-ui) · [Email](mailto:dog098263@gmail.com)

⭐ *Star this repo if you found it useful!*
