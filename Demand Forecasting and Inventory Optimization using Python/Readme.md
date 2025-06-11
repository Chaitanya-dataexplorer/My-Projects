# Demand Forecasting & Inventory Optimization using Python

This project focuses on predicting future customer demand and optimizing inventory levels using time series forecasting models and strategic stock management techniques. The goal is to reduce excess inventory, avoid stockouts, and improve operational efficiency in supply chains.

## 🧠 Project Overview

- **Demand Forecasting** estimates future product demand based on historical data.
- **Inventory Optimization** ensures that adequate stock is available to meet this demand without overstocking.

By combining both, businesses can improve customer satisfaction and reduce operational costs.

## 🔍 Workflow

1. **Data Loading & Cleaning**  
   Load and clean historical sales and inventory data.

2. **Visualization**  
   Time series visualization of demand and inventory trends.

3. **Forecasting Models**  
   Implemented models include:
   - SARIMA (Seasonal AutoRegressive Integrated Moving Average)
   - ACF and PACF plots for parameter tuning

4. **Inventory Optimization Strategies**  
   - Reorder point calculation  
   - Economic Order Quantity (EOQ)  
   - Safety stock estimation

## 📊 Libraries Used

- `pandas` and `numpy` for data manipulation
- `matplotlib` and `plotly` for visualization
- `statsmodels` for time series modeling (SARIMA)
- `os` for file operations

## 📁 Data

The dataset contains time-indexed data with columns like:
- `Date`
- `Demand`
- `Inventory`

Ensure your dataset is correctly formatted and stored locally with the path updated in the script.

## 🚀 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/demand-forecasting-inventory.git
    cd demand-forecasting-inventory
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook in Jupyter or VSCode:
    ```bash
    jupyter notebook "Demand Forecasting & Inventory Optimization.ipynb"
    ```

## 🧾 requirements.txt context

The project relies on specific libraries for data handling, statistical modeling, and plotting.

---
