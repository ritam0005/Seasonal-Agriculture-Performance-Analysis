# 🌾 Seasonal Agriculture Performance Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Analysis-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-purple)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 📌 Project Overview

The **Seasonal Agriculture Performance Analysis** project studies agricultural performance across three major agricultural seasons:

- 🌧️ Kharif
- ❄️ Rabi
- ☀️ Zaid

The project uses a dataset containing **4,000 farm records and 28 variables** covering environmental conditions, soil characteristics, resource usage, yield, production, economic performance, water efficiency, and disease/pest risk.

The analysis is performed using Python, exploratory data analysis, data visualization, correlation analysis, and statistical testing.

---

## 🎯 Objectives

- Explore and clean the agricultural dataset.
- Compare environmental conditions across seasons.
- Analyze fertilizer, pesticide, and water usage.
- Study irrigation methods.
- Compare yield and production.
- Analyze cost, revenue, and profit.
- Study relationships between agricultural conditions and outcomes.
- Analyze state-wise seasonal patterns.
- Examine disease and pest risk.
- Perform statistical analysis.
- Provide data-driven recommendations.

---

## 📊 Dataset

The dataset contains:

- **4,000 farm records**
- **28 variables**
- **3 agricultural seasons**

### Main Variables

| Category | Variables |
|---|---|
| Farm | Farm ID, State, District, Farm Area |
| Crop | Crop, Season |
| Environment | Rainfall, Temperature, Humidity, Sunlight |
| Soil | Soil pH, Soil Moisture, Nitrogen, Phosphorus, Potassium |
| Resources | Fertilizer, Pesticide, Irrigation |
| Production | Yield, Production |
| Economics | Market Price, Cost, Revenue, Profit |
| Water | Water Used, Water Efficiency |
| Risk | Disease/Pest Risk |

---

## 🧹 Data Cleaning

The project checks:

- Missing values
- Duplicate rows
- Duplicate Farm IDs
- Invalid numerical values
- Invalid percentage values
- Yield outliers

Missing values are handled using **Season + Crop group median imputation**, with an overall median fallback.

Negative profit values are retained because they can represent genuine farm losses.

---

## 🌦️ Environmental Analysis

The project compares:

- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil moisture
- Soil conditions

across Kharif, Rabi, and Zaid.

---

## 💧 Resource Usage Analysis

The project analyzes:

- Fertilizer usage
- Pesticide usage
- Water usage
- Water efficiency
- Irrigation methods

---

## 🌾 Yield & Production Analysis

The project compares:

- Yield in tonnes/hectare
- Total production
- Crop-wise seasonal yield
- Seasonal yield patterns

---

## 💰 Economic Analysis

The analysis evaluates:

- Total cost
- Revenue
- Profit
- Loss-making farms
- Seasonal economic performance

---

## 📈 Correlation Analysis

Correlation analysis is used to study relationships between important numerical variables such as environmental conditions, resource usage, yield, water efficiency, and profit.

Correlation is interpreted as association and not necessarily causation.

---

## 📊 Statistical Analysis

The project uses statistical testing to evaluate seasonal differences.

ANOVA is used for comparisons involving:

- Yield
- Profit

The significance level used is:

**α = 0.05**

---

## 🗺️ State-wise Analysis

Seasonal agricultural performance is also analyzed across states using **State × Season** comparisons.

This helps identify regional differences in agricultural performance.

---

## 🐛 Disease & Pest Risk

The project compares disease and pest risk across the three agricultural seasons.

---

## 💡 Recommendations

The analysis provides recommendations related to:

- Seasonal crop planning
- Water management
- Irrigation efficiency
- Agricultural resource management
- Disease and pest management
- Regional agricultural planning

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data Analysis |
| NumPy | Numerical Analysis |
| Matplotlib | Visualization |
| Seaborn | Visualization |
| SciPy | Statistical Analysis |
| Jupyter Notebook | Interactive Analysis |
| VS Code | Development |
| Git | Version Control |
| GitHub | Repository Hosting |

---

## 📂 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── data/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── notebooks/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── outputs/
│   └── charts/
│
├── screenshots/
│
├── .gitignore
├── README.md
└── requirements.txt