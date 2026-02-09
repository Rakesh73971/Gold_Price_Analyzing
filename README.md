
# 📊 Gold Price Data Visualization & Time Series Analysis

## 📌 Project Overview

This project focuses on **analyzing and visualizing gold price trends over time** using Python.
The goal is to understand **daily, monthly, quarterly, and yearly patterns**, along with **seasonality and variability** in gold prices through different visualization techniques.

---

## 🛠️ Tools & Libraries Used

* **Python**
* **Pandas** – data loading, manipulation, resampling
* **Matplotlib** – basic visualizations
* **Seaborn** – heatmap visualization
* **Statsmodels** – seasonal decomposition of time series

---

## 📂 Dataset

* **File:** `Gold Price.csv`
* The dataset contains **historical gold prices indexed by date**
* The date column is used as a **DatetimeIndex** for time-series resampling

---

## 🔍 Analysis Performed

### 1️⃣ Daily Gold Price Trend

* Visualized daily gold prices to observe short-term fluctuations and overall movement.

### 2️⃣ Monthly Mean Gold Price

* Resampled data using monthly frequency (`ME`)
* Calculated and plotted **average monthly gold prices** to identify medium-term trends.

### 3️⃣ Quarterly Mean Gold Price

* Resampled data quarterly (`QE`)
* Helped smooth short-term noise and highlight broader price movements.

### 4️⃣ Seasonal Decomposition

* Used **additive seasonal decomposition** to break gold prices into:

  * Trend
  * Seasonality
  * Residual (noise)
* This helps understand hidden patterns over time.

### 5️⃣ Yearly Maximum Gold Price

* Extracted and visualized **maximum gold price for each year** using a bar chart.

### 6️⃣ Yearly Distribution (Box Plot)

* Created box plots for each year to study:

  * Price spread
  * Median values
  * Outliers

### 7️⃣ Monthly-Yearly Heatmap

* Generated a **pivot table** with Month vs Year
* Visualized it using a heatmap to clearly show:

  * Seasonal price behavior
  * Year-wise variations

---

## 📈 Visualizations Included

* Line plots (Daily, Monthly, Quarterly)
* Bar chart (Yearly max price)
* Box plots (Year-wise distribution)
* Seasonal decomposition plots
* Heatmap (Monthly vs Year pricing)

---

## 🚀 Key Learnings

* Hands-on experience with **time-series resampling**
* Understanding **seasonality and trend analysis**
* Improved data storytelling using multiple visualization techniques
* Practical use of **pandas pivot tables and heatmaps**

---

## ▶️ How to Run the Project

1. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn statsmodels
   ```
2. Place `Gold Price.csv` in the project directory
3. Run the Python script or Jupyter Notebook

---
