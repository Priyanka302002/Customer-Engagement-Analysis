# 📊 Student Engagement Analysis  

This project involves analyzing the engagement of students with a platform over two years (Q4 2021 to Q4 2022) based on their subscription plans. The analysis focuses on descriptive statistics, confidence intervals, and hypothesis testing for both paid-plan and free-plan students.

## 📌 Table of Contents  

- [📖 Project Overview](#project-overview)  
- [📂 Data Description](#data-description)  
- [📊 Analysis](#analysis)  
  - [📈 Task 1: Descriptive Statistics](Descriptive_Statistics.xlsx)  
  - [📊 Task 2: Skewness and Kurtosis](Descriptive_Statistics.xlsx)  
  - [📉 Task 3: Confidence Intervals](Confidence_Intervals)  
  - [📑 Task 4: Hypothesis Testing](Hypothesis_Testing)  
- [📋 Results and Interpretation](#results-and-interpretation)  
- [✅ Conclusion](#conclusion)  
- [⚙️ How to Run the Code](#how-to-run-the-code)  

## 📖 Project Overview  

This project analyzes student engagement based on their subscription plans (Paid vs. Free). The goal is to examine engagement trends using statistical methods, including hypothesis testing, to determine if there were significant changes in engagement levels from Q4 2021 to Q4 2022.

## 📂 Data Description  

The dataset contains:  
- **🆔 Student ID**: Unique identifier for each student.  
- **💳 Plan Type**: Subscription plan (Paid or Free).  
- **⏳ Q4 2021 Minutes Watched**: Total minutes watched in Q4 2021.  
- **📺 Q4 2022 Minutes Watched**: Total minutes watched in Q4 2022.  

## 📊 Analysis  

### 📈 Task 1: Descriptive Statistics  

- **Paid-plan students**: Significant increase in engagement from Q4 2021 to Q4 2022.  
- **Free-plan students**: Average minutes watched increased, but median engagement decreased.  

### 📊 Task 2: Skewness and Kurtosis  

- **Paid-plan students**: Skewness increased from **0.63** (Q4 2021) to **7.07** (Q4 2022), indicating a right-skewed distribution.  
- **Free-plan students**: Skewness increased from **1.17** to **15.06**, suggesting a few students watched significantly more content.  

### 📉 Task 3: Confidence Intervals  

- **Paid-plan students**: The confidence interval suggests increased engagement.  
- **Free-plan students**: The confidence interval suggests lower engagement.  

### 📑 Task 4: Hypothesis Testing  

- **📊 F-test**: The null hypothesis of equal variances was rejected (**p-value = 0**).  
- **📉 Left-tailed t-test**: Paid-plan students in Q4 2022 had significantly higher engagement than free-plan students.  

## 📋 Results and Interpretation  

- **Paid-plan students**: Higher engagement increase.  
- **Free-plan students**: More variability in engagement.  
- **Hypothesis testing** confirmed statistically significant differences.  

## ✅ Conclusion  

Paid-plan students showed higher engagement growth, likely due to premium features. Free-plan students had more diverse engagement levels, indicating the need for engagement strategies.  

## ⚙️ How to Run the Code  

1. 📥 Clone the repository or download project files.  
2. 📂 Open **Excel files** (`Descriptive_Statistics.xlsx`, `Confidence_Intervals.xlsx`).  
3. 🧐 Review formulas and calculations.  
4. 🐍 Use **Python** for additional statistical tests (optional).  

## 🔧 Dependencies  

- 🖥 **Microsoft Excel** (for spreadsheet analysis)  
- 🐍 **Python** (for statistical tests, if needed)  

---  
🚀 **Happy Analyzing!** 📊  
