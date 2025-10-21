# Inventory Management using ABC Analysis and Pareto Principle

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pawan933-hash/INVENTORY-MANAGEMENT-USING-ABC-ANALYSIS-AND-PARETO-PRINCIPLE./blob/main/PARETO_ABC_ANALYSIS.ipynb)
---

## Overview 📝

This notebook performs **ABC Analysis** and **Pareto Analysis** on inventory transaction data (`transactions_100.csv`). It classifies items (SKUs) into A, B, and C categories based on their contribution to the total sales quantity over 100 days. The analysis helps prioritize inventory management efforts by identifying the most significant items (Class A) according to the Pareto Principle (80/20 rule).

---

## Key Concepts & Techniques 🛠️

* **ABC Analysis:** Categorizes inventory items into A (high value/volume), B (medium), and C (low) classes.
* **Pareto Principle:** Identifies the vital few items contributing to the majority of sales volume.
* **Coefficient of Variation (CV):** Measures demand variability for each item (Standard Deviation / Mean).
* **Data Analysis:** Uses `pandas` for data loading, manipulation, and statistical calculations.
* **Visualization:** Uses `matplotlib` to create a Pareto Chart and an ABC Chart (CV vs. % Sales).

---

## Prerequisites 📚

* Python 3
* Jupyter Notebook or Google Colab
* Libraries: `pandas`, `numpy`, `scipy`, `matplotlib`

Install libraries via pip:
```bash
pip install pandas numpy scipy matplotlib
