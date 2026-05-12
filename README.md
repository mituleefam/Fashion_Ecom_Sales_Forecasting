# Fashion E-commerce Sales Forecasting - VinUni Datathon

This repository contains the solution by team **EntropyZero** for the VinUni Datathon, focusing on Fashion E-commerce Sales Forecasting. The objective is to forecast future Revenue and COGS (Cost of Goods Sold) based on historical sales, inventory, and customer data.

## 📂 Project Structure

```text
├── data/                  # Raw dataset files (customers, orders, inventory, etc.)
├── notebooks/             # Jupyter Notebooks for analysis and modeling
│   ├── eda/               # Exploratory Data Analysis notebooks
│   └── modeling/          # Model training, evaluation, and reporting
├── outputs/               # Generated artifacts (submission files, plots, model metrics)
├── venv/                  # Python virtual environment
└── catboost_info/         # CatBoost training logs
```

## 🚀 How to Run

1. **Environment Setup:**
   Activate the virtual environment located in the `venv/` folder.
   - **Windows:** `.\venv\Scripts\activate`
   - **Mac/Linux:** `source venv/bin/activate`

2. **Data Preparation:**
   Ensure all competition dataset CSV files (e.g., `orders.csv`, `customers.csv`, `inventory.csv`) are placed inside the `data/` directory.

3. **Exploratory Data Analysis (EDA):**
   Navigate to `notebooks/eda/` and run the notebooks (like `Basic_EDA.ipynb` or `1st_EDA.ipynb`) to explore data insights, visualize trends, and understand the core features.

4. **Modeling & Prediction:**
   Open `notebooks/modeling/Model.ipynb` to execute the data processing and machine learning pipeline. The project leverages ensemble models like **XGBoost, LightGBM, and CatBoost**.
   - The final submission file (`submission.csv`), evaluation reports, and feature importance visualizations will be automatically saved to the `outputs/` directory.
