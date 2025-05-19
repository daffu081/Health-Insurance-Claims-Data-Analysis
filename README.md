# Insurance-Claims-Data-Analysis


# Insurance Data Statistical Analysis

**Author:** Sabbir Ahmed Sakib  
**ID:** 2410  
**Assignment:** Stat_Assignment_4  
**Dataset:** `insurance.csv`

---

## 📄 Overview

This project performs an exploratory data analysis and statistical hypothesis testing on a dataset of insurance beneficiaries. The goal is to uncover patterns in medical costs based on demographic and lifestyle variables such as age, gender, BMI, number of children, smoking status, and region.

---

## 📊 Dataset Description

The dataset contains information on **1,338 individuals** with the following columns:

- `age`: Age of the individual (18 to 64)
- `sex`: Gender (`male`, `female`)
- `bmi`: Body Mass Index (15.96 to 53.13)
- `children`: Number of dependents (0 to 5)
- `smoker`: Smoking status (`yes`, `no`)
- `region`: Residential region (`northeast`, `northwest`, `southeast`, `southwest`)
- `charges`: Medical insurance charges billed

---

## 🔍 Key Questions and Findings

1. **Gender Distribution**
   - Male: 676, Female: 662  
   - _Slightly more male beneficiaries, but overall balanced._

2. **Smoking Status**
   - Smokers: 274, Non-Smokers: 1,064  
   - _About 20.5% are smokers._

3. **Average Medical Charges by Region**
   - Highest: Southeast — $14,735.41  
   - Lowest: Northwest — $12,417.58  
   - _Regional disparities in average medical costs._

4. **Age Distribution**
   - Most beneficiaries are in their 20s to 50s.  
   - _Age is normally distributed with a slight peak in early adulthood._

5. **Dependents vs. Charges**
   - Charges not strongly linked to number of children.  
   - _Smokers consistently show higher charges._

6. **Smokers vs. Non-Smokers (T-test)**
   - **Result:** Statistically significant (p < 0.05)  
   - _Smokers incur significantly higher medical costs._

7. **BMI by Gender (T-test)**
   - **Result:** Not significant (p = 0.09)  
   - _No significant BMI difference between males and females._

8. **Smoker Proportion by Region (Chi-square)**
   - **Result:** Not significant (p = 0.0617)  
   - _Smoking prevalence is similar across regions._

9. **BMI by Number of Children (Females Only, ANOVA)**
   - **Result:** Not significant (p = 0.72)  
   - _BMI does not vary significantly with number of children._

---

## 🧪 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy.stats`

---

## 📁 How to Run

1. Upload the `insurance.csv` dataset to your environment (e.g., Colab).
2. Run the script provided in the notebook or `.py` file.
3. All visualizations and statistical results will be printed and plotted.

---

## ✅ Conclusion

The analysis confirms that **smoking** is a major contributor to increased medical charges. Gender, number of dependents, and regional differences have relatively lesser impacts. Statistical testing was used to validate all assumptions with proper hypothesis testing methods (T-test, ANOVA, Chi-square).

---

