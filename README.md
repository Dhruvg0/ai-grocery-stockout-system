# 🛒 AI Grocery Stock-Out Prediction System

An AI-powered inventory monitoring and stock-out risk prediction system built using real-world grocery demand data.

## 🚀 Problem Statement
Essential goods often face unexpected stock-outs due to fluctuating demand and poor inventory planning. This leads to supply disruptions, increased costs, and reduced food security.

## 💡 Solution Overview
This project analyzes historical grocery sales data to:
- Forecast short-term demand using rolling averages
- Simulate inventory buffers
- Predict stock-out risks (High / Medium / Low)
- Visualize risks through an interactive dashboard

## 🧠 Key Features
- 📊 Demand analysis using real Kaggle dataset  
- 🔁 Rolling average demand forecasting  
- 📦 Inventory simulation with safety buffers  
- 🚨 Stock-out risk classification  
- 🖥️ Interactive Streamlit dashboard  

## 🛠️ Tech Stack
- Python
- Pandas, Matplotlib
- Streamlit
- Git & GitHub

## Dataset

This project uses the **Store Item Demand Forecasting Challenge** dataset from Kaggle.

Due to licensing restrictions, the dataset is not included in this repository.

### Steps to get the data:
1. Visit: https://www.kaggle.com/c/demand-forecasting-kernels-only/data
2. Download `train.csv`
3. Create a folder named `data/` in the project root
4. Place `train.csv` inside the `data/` folder


## ▶️ How to Run
```bash
pip install -r requirements.txt
python -m streamlit run app.py


