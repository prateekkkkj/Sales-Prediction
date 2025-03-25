# 📊 Sales Prediction using Machine Learning

## 🚀 Project Overview
This project aims to forecast **car purchase amounts** using machine learning based on historical sales data. By analyzing factors such as **advertising spend, promotions, customer demographics**, and more, businesses can optimize their marketing strategies for **sales growth**.

## 📂 Repository Structure
```
📂 Sales-Prediction-Project
│── 📄 README.md             # Project documentation
│── 📄 sales_prediction.ipynb # Jupyter Notebook with full implementation
│── 📄 requirements.txt       # Dependencies (pandas, sklearn, matplotlib, etc.)
│── 📂 data
│   ├── car_purchasing.csv   # Original dataset
│── 📂 models
│   ├── final_model.pkl      # Trained model for deployment
│── 📂 visualizations
│   ├── predictions_vs_actual.png # Graphs from EDA & model evaluation
```

## 📊 Data Analysis & Preprocessing
- **Handled missing values** and detected **outliers**.
- **Encoded categorical variables** (Country, Gender) for numerical compatibility.
- **Scaled numerical features** (Salary, Debt, Net Worth, etc.) using **MinMaxScaler**.

## 🔍 Models Used & Performance
| Model               | **MSE (Lower is Better)** | **R² Score (Closer to 1 is Better)** |
|---------------------|-------------------------|----------------------------------|
| **Linear Regression** | **2.10**                | **0.99999** (Best Fit!)         |
| **Random Forest**     | **5,540,245.10**        | **0.9487**                      |
| **Decision Tree**     | **7,832,410.45**        | **0.9189**                      |
| **XGBoost**          | **180.12**               | **0.9995** (Highly Accurate)    |

**Final Model Selected: XGBoost (Best tradeoff between performance & generalization).**

## 🛠 How to Run the Project
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 2️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```
### 3️⃣ Train & Evaluate Models
Open **`sales_prediction.ipynb`**, run all cells, and analyze results.

## 📌 Conclusion
This model effectively predicts car purchase amounts, helping businesses optimize marketing strategies and boost sales. Future improvements could involve **hyperparameter tuning, feature engineering, and real-time model deployment.** 🚀

