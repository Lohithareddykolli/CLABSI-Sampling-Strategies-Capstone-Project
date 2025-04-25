# CLABSI Sampling Strategies – Capstone Project

This repository contains the code, dataset, and final report for our **Capstone I project** at the **University of Houston**, focused on evaluating sampling methods for estimating **Central Line-Associated Bloodstream Infections (CLABSI)** from a highly imbalanced healthcare dataset.

---

## 📌 Project Overview

Healthcare datasets often suffer from class imbalance, especially in rare but critical outcomes like CLABSI. Accurate estimation of such events is essential for reliable predictive modeling and improved patient safety.

This project explores and compares **Simple Random Sampling** and **Stratified Random Sampling** to create representative subsets from a pediatric hospital dataset containing over 5,000 patient records.

---

## 🎯 Objectives

- Analyze the skewed distribution of CLABSI events in the dataset.
- Apply probabilistic sampling techniques to extract 10% representative samples.
- Compare statistical properties (mean, variance, skewness) of sample vs. population.
- Conduct hypothesis testing to validate sample representativeness.
- Recommend the most appropriate sampling strategy for downstream modeling.

---

## 🧠 Key Insights

- The dataset has a strong right-skew, with <3% of patients experiencing CLABSI.
- **Simple Random Sampling** is efficient but may underrepresent rare CLABSI cases.
- **Stratified Random Sampling** ensures proportional representation of rare events.
- Hypothesis testing showed both samples statistically align with the population.
- Stratified sampling is more robust for modeling rare healthcare events.

---

## 📁 Project Structure


---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, SciPy)
- **Excel** (RAND function, sampling setup)
- **Jupyter Notebook** for analysis and visualization
- **Statistical Methods**: Descriptive statistics, t-tests
- **Visualization**: Histograms, distribution plots

---

## 📊 Sampling Techniques

### 1. Simple Random Sampling (SRS)
- Every patient has an equal chance of being selected.
- Implemented using Excel’s `RAND()` function.
- Easy and fast, but may miss rare CLABSI cases due to imbalance.

### 2. Stratified Random Sampling
- Patients are split into strata: CLABSI-positive and CLABSI-negative.
- Ensures proportional inclusion of both subgroups.
- More accurate for modeling rare outcomes, but setup is more complex.

---

## 📈 Statistical Validation

- Both sampling methods were evaluated using descriptive statistics and t-tests.
- Metrics compared: Mean, Median, Mode, Standard Deviation, Variance, Kurtosis, Skewness.
- Results confirm stratified sampling offers closer alignment to population metrics.


## ⭐ Acknowledgements

- Thanks to the faculty of the University of Houston for their support and guidance.
- This project was conducted as part of the **BZAN 6360 – Capstone Practicum in Business Analytics I**.

---

> *"Better sampling leads to better predictions—especially when every case matters in healthcare."*
