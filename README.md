# Vehicle Market Analysis

## Project Description

This project analyzes vehicle listings collected from **Bama.ir** to identify key factors associated with vehicle prices.

The dataset contains information such as vehicle price, manufacturing year, mileage, fuel type, transmission, body condition, engine specifications, authentication status, and vehicle descriptions.

The analysis covers:

* Data Understanding and Cleaning
* Missing Value Analysis
* Feature Engineering
* Outlier Detection and Treatment
* Exploratory Data Analysis (EDA)
* Brand Analysis
* Price Distribution Analysis
* Correlation and Comparative Analysis

The project focuses on understanding how vehicle characteristics such as **brand, age, mileage, transmission type, and fuel type** are associated with market listing prices.

---

## Key Insights

* Vehicle prices are highly right-skewed, and log transformation improves distribution symmetry.
* Newer vehicles generally have higher prices.
* Higher mileage is associated with lower prices.
* Automatic vehicles tend to have higher prices than manual vehicles.
* Electric and hybrid vehicles show higher average prices in the analyzed dataset.
* Brand positioning is strongly associated with vehicle price differences.

---

## Dataset

The dataset consists of vehicle listings collected from **Bama.ir**.

It includes vehicle characteristics, listing information, and price data.

Listings with negotiable or undisclosed prices were treated as missing for price-based analyses. Unrealistic price records identified through statistical analysis and manual inspection were removed.

The dataset is not included in this repository.

---

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Repository Structure

```text
vehicle-market-analysis/
├── README.md
├── notebooks/
│   └── vehicle_market_analysis.ipynb
└── figures/
    ├── ...
    └── ...
```

---

**Author:** Sina Rastegar
**Date:** July 10, 2026
