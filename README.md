# california-housing-price-prediction
Machine Learning project to predict median house prices in California using Linear Regression, Random Forest, and XGBoost. Achieved RMSE: 0.437 and R²: 0.854 with tuned XGBoost.
# California Housing Price Prediction

**Predicting median house values in California using Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-35495E?style=for-the-badge&logo=xgboost&logoColor=white)

---

## 📋 Project Overview

This project aims to predict the median house prices in California districts by experimenting with different machine learning algorithms. I built separate notebooks for each approach — from basic Linear Regression to advanced XGBoost with hyperparameter tuning.

**Best Model Performance:**
- **XGBoost (Tuned)** → **RMSE: 0.437** | **R² Score: 0.854**

---

## 📊 Models & Notebooks

| Notebook No | Notebook Name                                              | Model                  | RMSE    | R² Score |
|-------------|-----------------------------------------------------------|------------------------|---------|----------|
| 1           | California Housing price prediction using linear regression | Linear Regression     | 0.733   | 0.597    |
| 2           | California Housing price prediction using linear regression and feature engineering | Linear Regression + FE | -       | -        |
| 3           | California Housing price prediction using random forest   | Random Forest         | 0.503   | 0.807    |
| 4           | California Housing price prediction using XGBoost         | XGBoost (Tuned)       | **0.437** | **0.854** |

---

## 🗂️ Project Structure
california-housing-price-prediction/
├── notebooks/
│   ├── California Housing price prediction using linear regression.ipynb
│   ├── California Housing price prediction using linear regression and feature engineering.ipynb
│   ├── California Housing price prediction using random forest.ipynb
│   └── California Housing price prediction using XGBoost.ipynb
├── README.md
├── requirements.txt
└── .gitignore




---

## 🛠️ How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/adas1496/california-housing-price-prediction.git

2. Install Dependencies
   pip install -r requirements.txt

3. Run the Notebooks
Open the notebooks/ folder and run the notebooks in this order:
- California Housing price prediction using linear regression.ipynb
- California Housing price prediction using linear regression and feature engineering.ipynb
- California Housing price prediction using random forest.ipynb
- California Housing price prediction using XGBoost.ipynb

 Key Learnings
- Feature Engineering played a major role in improving model accuracy
- Tree-based ensemble models (Random Forest & XGBoost) significantly outperformed Linear Regression
- Hyperparameter tuning helped boost the performance of XGBoost

Future Improvements
- Try LightGBM and CatBoost
- More advanced feature engineering
- Model deployment using Streamlit or FastAPI
- Better handling of capped target values

