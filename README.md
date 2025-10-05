# datafun-07-ml
# Predictive ML Project (Module 7)

**Author:** Bakhrom Botirov  
**Course:** Data Analytics Fundamentals  
**Institution:** Northwest Missouri State University  
**Instructor:** Professor Denise Case  
**Date:** October 2025  

---

## Project Overview
This project explores **supervised machine learning** using **simple linear regression** to analyze temperature trends and make predictions.  
It is based on Chapter 10 (Time Series and Linear Regression) and Chapter 15 (Machine Learning) from *Intro to Python for Computer Science and Data Science* by Deitel & Deitel.

---

## Repository
GitHub Repository:  
[https://github.com/batyrovbahrom96-svg/datafun-07-ml](https://github.com/batyrovbahrom96-svg/datafun-07-ml)

---

## Objectives
1. Build and evaluate a linear regression model.  
2. Predict future temperature values using historical data.  
3. Visualize data and model trends using Seaborn and Matplotlib.  
4. Compare two regression methods:  
   - **SciPy’s `linregress()`**  
   - **scikit-learn’s `LinearRegression`**  

---

## Tools & Libraries
- **Python 3.11**  
- **pandas** for data manipulation  
- **NumPy** for numerical operations  
- **SciPy** for statistical regression  
- **scikit-learn** for machine learning  
- **Seaborn** and **Matplotlib** for visualization  

---

## Data Source
Dataset:  
[NYC January Average High Temperatures 1895–2018 (CSV)](https://raw.githubusercontent.com/pdeitel/IntroToPython/master/examples/ch15/ave_hi_nyc_jan_1895-2018.csv)

Each record includes:
- **Date (Year)**
- **Average High Temperature (°F)**
- **Anomaly** (Temperature deviation from long-term mean)

---

## Project Parts

### **Part 1 – Chart a Straight Line**
Used basic plotting to show a simple linear relationship (Celsius vs Fahrenheit).

### **Part 2 – Prediction Using SciPy**
- Built a regression model using `scipy.stats.linregress`.
- Predicted NYC January high temperature for **2024 = ~38.6°F**.
- Visualized trend with Seaborn regression plot.

### **Part 3 – Prediction Using scikit-learn**
- Split data into **training** and **testing** sets.
- Trained `LinearRegression()` model.
- Predicted 2024 temperature = **~38.5°F**.
- Visualized regression and testing performance.

### **Part 4 – Insights**
- Both SciPy and scikit-learn produced nearly identical results.
- The long-term trend shows a gradual temperature increase.
- Demonstrated practical ML workflow and data visualization.

---

## Results
| Method | Library Used | Predicted 2024 Temp (°F) | Notes |
|---------|---------------|--------------------------|-------|
| Part 2 | SciPy | 38.6 | Simpler statistical regression |
| Part 3 | scikit-learn | 38.5 | Includes training/test split |

---

## Key Takeaways
- Linear regression is a strong baseline model for trend analysis.  
- Visualizing data helps confirm the accuracy of predictions.  
- Both SciPy and scikit-learn use the same mathematical foundation but serve different purposes:
  - SciPy for quick statistical modeling.
  - scikit-learn for scalable, production-level ML.

---

## Future Improvements
- Apply non-linear regression (polynomial or exponential models).  
- Add monthly data for seasonal analysis.  
- Extend to real-time temperature prediction using API data.  

---

## Contact
**Bakhrom Botirov**  
Email: [s585760@nwmissouri.edu](mailto:s585760@nwmissouri.edu)
