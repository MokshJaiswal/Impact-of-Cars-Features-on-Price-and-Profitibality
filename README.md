# 🚗 Car Features vs Price & Profitability Analysis

An end-to-end data analytics project that investigates how car features impact pricing and profitability. This project simulates the role of a **Data Analyst** working with an automotive manufacturer to drive product and pricing decisions using data-backed insights.

---

## 🧠 Project Overview

The automotive industry is transforming with rising competition, innovation in electric vehicles (EVs), and evolving customer preferences. This project addresses a key business question:

> **"How can a car manufacturer optimize pricing and product development to maximize profitability while meeting consumer demand?"**

Using a real-world-like dataset and Excel + statistical tools, we uncover patterns between **vehicle features**, **fuel types**, **market categories**, and their **pricing and profitability impact**.

---

## 📊 Problem Scope

- Understand how different features (e.g., engine type, transmission, fuel grade) influence **car price**.
- Segment the market to identify **high-profit** and **high-demand** vehicle categories.
- Build a **pricing strategy** that aligns profitability with consumer demand.
- Derive **feature-based recommendations** for future product development.

---

## 🗃️ Dataset Summary

| Column                | Description                                  |
|-----------------------|----------------------------------------------|
| Make                  | Manufacturer (e.g., Toyota, Ford)            |
| Model                 | Car model                                    |
| Year                  | Model year                                   |
| Engine Fuel Type      | Type of fuel (Gasoline, Electric, etc.)      |
| Engine HP             | Horsepower                                   |
| Transmission Type     | Automatic, Manual, CVT, etc.                 |
| Driven Wheels         | FWD, RWD, AWD                                 |
| Number of Doors       | 2, 4, etc.                                    |
| Market Category       | Luxury, Crossover, Hybrid, etc.              |
| Vehicle Size          | Compact, Midsize, Large                      |
| Price                 | Market price of vehicle ($)                  |
| MSRP                  | Manufacturer’s Suggested Retail Price ($)    |

---

## 🔍 Key Analytical Components

### ✅ Data Analytics
- 🚘 **Feature-Pricing Correlation**: Explored how horsepower, transmission, and fuel type influence price.
- 🏷️ **Category Profitability**: Mapped market segments to pricing and MSRP margins.
- 📊 **Outlier Detection**: Identified anomalies using boxplots and z-scores.
- 🔎 **Regression Models**: Built linear regressions to predict price based on features.

### ✅ Advanced Excel
- 📈 Created **Pivot Tables** to group features and compare average price/MSRP.
- 💡 Used **VLOOKUP**, **IF**, **AVERAGEIFS**, **COUNTIFS**, **INDEX/MATCH** for feature-wise aggregations.
- 📊 Created dynamic dashboards and filters for exploratory analysis.

### ✅ Statistics & Visualization
- 📉 Correlation matrix to show strength of feature-price relationships.
- 📊 Bar charts, box plots, and scatterplots to visualize distribution and outliers.
- 🧮 Basic regression (R² ~0.82) and descriptive statistics for market segments.

---

## 💡 Sample Insights

- Cars with **AWD and Turbocharged Engines** had on average a **15–20% higher MSRP**.
- **Electric vehicles** showed the **highest margin** but lowest volume (niche market).
- **Luxury SUVs** had the **highest profitability-to-demand ratio**, suggesting a strategic opportunity.
- Cars with **manual transmission** and **lower horsepower** saw the **lowest average margins**.

---

## 🧰 Tools & Skills Used

- **Microsoft Excel (Advanced Functions, Dashboards, Regression Toolpak)**
- **Statistical Analysis (Descriptive Stats, Linear Regression, Z-scores)**
- **Data Cleaning and Feature Engineering**
- **Data Visualization (Pivot Charts, Scatter Plots, Histograms)**

---

## 📁 Folder Structure

```

car-features-pricing-analysis/
├── data/
│   └── car\_data\_cleaned.xlsx
├── excel\_outputs/
│   ├── dashboards/
│   ├── pivot\_tables/
│   └── regression\_model.xlsx
├── visualizations/
│   └── charts/
├── README.md

```

---

## 📈 Results & Recommendations

This project helped simulate real-world product analytics in the automotive domain:

- Identified top-performing product categories in terms of **profitability** and **consumer interest**.
- Provided **data-driven recommendations** to prioritize development of **luxury compact hybrids** and **AWD sedans**.
- Highlighted cost-saving opportunities by minimizing **low-margin variants**.

---

## 📜 License

This project is intended for educational and portfolio use. All data used is synthetic or anonymized.

---

## 🙌 Acknowledgements

Project completed as part of Final Project-3 – **Advanced Excel & Data Analysis** coursework. Inspired by real-world product pricing challenges in the auto industry.
