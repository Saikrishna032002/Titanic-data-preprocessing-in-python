# 🚢 Titanic Survival Analysis Project

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on the classic [Titanic dataset](https://www.kaggle.com/c/titanic) to identify key factors influencing passenger survival. The analysis uses Python with **Pandas**, **Seaborn**, and **Matplotlib** to visualize survival rates across demographic and socio-economic features.

<img width="1016" height="500" alt="image" src="https://github.com/Saikrishna032002/Titanic-data-preprocessing-in-python/blob/f068952f4457c58434d9c60a70e64c169594604d/titanic.jpg" />


## 📊 Key Visualizations & Findings

| Feature Analyzed | Plot Type | Key Finding |
| :--- | :--- | :--- |
| **Survival vs. Gender & Class** | Clustered Bar Chart | Women (especially 1st & 2nd Class) had vastly higher survival rates than men. |
| **Fare vs. Passenger Class** | Box Plot / Swarm Plot | Fare distribution varied strongly by class; 1st Class had the widest range and highest median fare. |
| **Age vs. Survival** | KDE / Histogram | Very young children had a significantly higher survival rate than most other age groups. |
| **Missing Data** | Bar Chart | **Third Class** had the highest count of missing 'Age' values ($\approx 135$). |

---

## 🛠️ Project Structure & Setup

### Prerequisites

You need the following Python libraries installed:

```bash
pip install pandas seaborn matplotlib
