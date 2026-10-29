# SalesVision-Sales-Forecasting
Python-based sales forecasting and revenue analytics using Pandas, data visualization, and time-series models.

# 📊 SalesVision: Sales Forecasting & Revenue Analytics

**SalesVision** is a Python-based data analytics project that explores historical retail sales, identifies revenue trends, compares product and regional performance, and forecasts future monthly sales.

The goal of this project is to demonstrate practical skills in **data cleaning, exploratory data analysis (EDA), data visualization, and time-series forecasting**.

## 🎯 Project Objectives

- Clean and prepare retail sales data for analysis.
- Analyze monthly sales and revenue trends.
- Compare sales performance across product categories and regions.
- Build a monthly revenue time series.
- Compare multiple forecasting techniques.
- Evaluate forecast performance using MAE and RMSE.
- Generate a six-month sales forecast to support business planning.

## 🛠️ Technologies Used

- **Python** — data analysis and forecasting
- **Pandas & NumPy** — data manipulation and numerical operations
- **Matplotlib & Seaborn** — data visualization
- **Statsmodels** — time-series forecasting
- **Jupyter Notebook** — interactive analysis and documentation

## 📈 Project Workflow

1. **Data Collection:** Load the retail sales dataset.
2. **Data Cleaning:** Process dates, check data quality, and prepare the sales data.
3. **Exploratory Data Analysis:** Explore revenue trends and category and regional performance.
4. **Time-Series Preparation:** Aggregate sales into monthly revenue totals.
5. **Model Development:** Compare baseline forecasting methods with Holt-Winters exponential smoothing.
6. **Model Evaluation:** Evaluate predictions using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
7. **Forecasting:** Generate a forecast for the next six months.

## 🔍 Key Features

- Monthly revenue trend analysis
- Product category performance analysis
- Regional sales comparisons
- Time-series forecasting
- Forecast model comparison
- Visual representation of historical and forecast sales

## 📂 Repository Structure

```text
SalesVision-Sales-Forecasting/
│
├── README.md
├── SalesVision_Sales_Forecasting.ipynb
└── data/
    └── train_india.csv  # Local dataset; not included in the public repository
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/SalesVision-Sales-Forecasting.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn jupyter
```

### 3. Prepare the dataset

Place an authorized copy of the dataset in the `data/` folder with the filename `train_india.csv`, or update the file path in the notebook.

The dataset should contain the order date and sales amount fields expected by the notebook.

