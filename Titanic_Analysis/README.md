# 🚢 Titanic Data Analysis using Inferential Statistics

## 📊 Project Overview

This project applies **inferential statistical techniques** on the Titanic dataset to draw meaningful conclusions about passenger survival.

The goal is not just analysis, but to **understand how statistical methods help in making real-world inferences from sample data**.

---

## 🎯 Objectives

* Understand dataset structure and missing values
* Perform **sampling and compare with population**
* Demonstrate **Central Limit Theorem (CLT)**
* Compute **confidence intervals**
* Conduct **hypothesis testing**
* Interpret results in a real-world context

---

## 🧠 Concepts Covered

* Sampling techniques
* Central Limit Theorem
* Confidence Intervals (95%)
* Hypothesis Testing (t-test)
* p-value interpretation
* Statistical decision-making

---

## 🧹 Data Cleaning

* Handled missing values:

  * `Age` → Filled using median / grouped median
  * `Embarked` → Filled using mode
  * `Cabin` → Dropped due to excessive missing values

---

## 📌 Key Analysis

### 🔹 Sampling

* Random sample of 100 observations taken
* Compared sample mean with population mean

---

### 🔹 Central Limit Theorem

* Generated **500 samples (size = 30)**
* Observed that distribution of sample means approaches normal distribution

---

### 🔹 Confidence Interval

* Calculated 95% confidence interval for Age
* Interpreted the range of true population mean

---

### 🔹 Hypothesis Testing

* Tested whether **gender affects survival**
* Used **independent t-test**

📌 Result:

* p-value < 0.05
* Rejected null hypothesis
* Concluded that gender significantly affects survival

---

## 📈 Key Insights

* Female passengers had higher survival rates
* Sampling distributions follow normal behavior (CLT)
* Larger samples give more reliable estimates
* Statistical tests help validate assumptions with data

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

---

## 🙏 Acknowledgment

Special thanks to **Girish Sir**, mentor at **Unlox Academy**, for guidance and support in understanding inferential statistics concepts.

---

## 🚀 Conclusion

This project demonstrates how statistical methods can be used to extract insights and make data-driven decisions, even with limited sample data.

---

## 📎 Dataset

Titanic Dataset (Kaggle)

---

📌 Why this project matters?
This project demonstrates how statistical methods help in making data-driven decisions from samples, which is essential in real-world analytics.

---

## 💡 Future Improvements

* Apply advanced statistical tests
* Feature engineering for better insights
* Build predictive models

---
