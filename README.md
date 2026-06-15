# Telecom Data Analytics Project

## Overview

This project is an end-to-end data analytics study designed to optimize business decision-making for a telecommunications company. By analyzing customer complaint datasets, this project uncovers actionable insights, builds predictive models for customer satisfaction, and utilizes linear programming for revenue optimization.

## Project Structure

The repository is organized to separate analysis from dependency management:

* `Descriptive_Analysis.ipynb`: Contains the Exploratory Data Analysis (EDA), visualization techniques, and statistical measures used to understand complaint patterns.


* `Predective_and_Prescreptive_Analysis.ipynb`: Contains the implementation of machine learning regression models for predicting customer satisfaction, including feature selection and model performance evaluation, alongside linear programming optimization for maximizing product revenue.


* `requirements.txt`: Contains the list of Python dependencies required to run the analysis environments.


* `Analysis/`: Contains the analysis plots.



## Key Analytics Phases

This project covers the three fundamental pillars of data analytics:

1. **Descriptive Analytics:**
* Performed data cleaning, outlier detection, and distribution analysis.


* Applied measures of frequency, central tendency, and dispersion to quantify customer behavior.


* Utilized visual tools (bar charts, pie charts, and heatmaps) to uncover dependencies between features like complaint type and escalation status.




2. **Predictive Analytics:**
* Developed regression models to forecast `Customer Satisfaction Scores`.


* Employed `SelectFromModel` and `Forward Sequential Feature Selector` to optimize predictive features.


* Compared model performance (Linear Regression, Random Forest, SVR) using RMSE, MAE, MSE, and R-Squared evaluation metrics.




3. **Prescriptive Analytics:**
* Implemented Linear Programming via the `scipy` library to maximize profit.


* Determined the optimal product allocation mix under capacity constraints (500,000 GB limit).





## Technologies & Tools

* **Data Processing:** Python, Pandas, NumPy


* **Statistical Analysis:** SciPy


* **Machine Learning:** Scikit-learn


* **Visualization:** Matplotlib, Seaborn



## Insights & Decision Support

* **Complaint Resolution:** Technical complaints dominate the dataset (>70%), suggesting a need for infrastructure-focused improvements.


* **Predictive Power:** The **Random Forest Regressor** demonstrated the highest precision in predicting customer satisfaction, serving as the recommended tool for future forecasting.


* **Optimization:** Prescriptive modeling identified the 180 GB mobile product as the primary profit driver, providing a clear path for future product prioritization.



---

*Note: This project was conducted as part of the Data Analytics coursework at Al Hussein Technical University (HTU).*

---
