# Bollywood Movie Data Analysis 🎬

## Project Overview

This project presents an in-depth exploratory data analysis (EDA) of a dataset focusing on Bollywood movies released between 2013 and 2015. The primary objective is to apply data manipulation, analysis, and visualization techniques to uncover meaningful insights. The analysis investigates relationships between movie budgets, box office collections, genre performance, and other factors that contribute to a film's commercial success.

---

## Dataset

The analysis is performed on the `bollywood.csv` dataset. This dataset contains various attributes for each movie, including release dates, genres, budget, box office revenue, and YouTube trailer metrics from a sample of **149 movies**.

---

## Tools and Libraries 💻

* **Python:** The core language used for the analysis.
* **Pandas:** For efficient data manipulation, cleaning, and analysis.
* **Seaborn & Matplotlib:** For creating informative and appealing data visualizations.
* **Google Colab / Jupyter Notebook:** As the interactive development environment for the project.

---

## Key Findings with Output 📊

* **Genre Dominance:** The analysis revealed that **'Drama'** was the most frequent genre, accounting for **35 movies** in the dataset, followed closely by 'Comedy' and 'Action'.

* **Top Profitability (ROI):** After engineering a Return on Investment (ROI) metric, the analysis identified the most profitable films. The film **'Aashiqui 2'** topped the charts with an exceptional ROI of over **650%**, demonstrating high returns on a modest budget.

* **Budget Distribution:** A histogram of movie budgets showed a strong right-skewed distribution. The vast majority of films were produced with a budget under **₹40 Crores**, while only a few high-budget films (over ₹100 Crores) acted as outliers.

* **Strategic Release Timing:** Movies released during a **'Festive Season'** showed the highest average ROI (**95%**), significantly outperforming movies released during a 'Long Weekend' (60%) or a 'Normal' period (45%).

* **Digital Engagement Impact:** A correlation analysis found a moderately strong positive correlation coefficient of **+0.68** between YouTube trailer likes and box office collections, confirming that higher online engagement is a significant indicator of a film's potential commercial success.
