# Drug-data-exploration

# 📊 Substance Use Patterns Among Emerging Adults

## 🔎 Project Overview

This project explores patterns of lifetime substance use among emerging
adults (ages 18–25), with a focus on understanding how demographic and
educational factors relate to the number of different substances used.

The analysis examines differences in lifetime drug use according to:

- Gender
- Race/ethnicity
- College enrollment status

The project was completed in R as part of graduate-level statistical
coursework.

---

## 🎯 Research Questions

1. How is lifetime drug use distributed among emerging adults?
2. Does lifetime drug use differ by gender?
3. Are there differences in lifetime drug use across racial/ethnic groups?
4. Is college enrollment associated with differences in lifetime drug use?

---

## 📁 Data

The analysis included **261 young adults**.

The primary outcome was:

**TOTALDRUGS** — total number of different drugs an individual reported
using during their lifetime, ranging from 0 to 12.

Predictors examined included:

- **GENDER** — male or female
- **RACE** — White/Caucasian, Asian/Pacific Islander,
  Black/African American, or Mixed Race
- **SCHOOL** — current college/university enrollment status

---

## 🛠️ Statistical Methods

The analysis was conducted in **R** using descriptive and exploratory
data analysis techniques, including:

- Descriptive statistics
- Data visualization with `ggplot2`
- Histograms and bar charts
- Boxplots
- Distributional analysis
- Group comparisons

---

## 📈 Key Findings

The average number of substances used was **2.72 (SD = 2.21)**,
with a median of 2 and a range of 0–12.

The distribution of lifetime drug use was strongly right-skewed, with
most participants reporting use of between 0 and 4 substances.

Exploratory comparisons showed:

- Males had a higher median number of substances used than females.
- Participants not enrolled in school had a higher median than those
  currently enrolled.
- Median lifetime drug use was similar across the racial/ethnic groups
  examined.

These findings are descriptive and should not be interpreted as
establishing causal relationships.

---

## 📊 Visualizations

### Distribution of Lifetime Drug Use

![Distribution of Lifetime Drug Use](figures/drug_distribution.png)

### Drug Use by Gender

![Drug Use by Gender](figures/drug_use_gender.png)

### Drug Use by Race

![Drug Use by Race](figures/drug_use_race.png)

### Drug Use by School Enrollment

![Drug Use by School Enrollment](figures/drug_use_school.png)

---

## 💡 Statistical Considerations

Because the outcome represents a count and exhibits substantial
right-skewness, future inferential analysis could consider count
regression approaches such as **Poisson or Negative Binomial
regression**, with appropriate assessment of model assumptions and
dispersion.

---

## 💻 Tools & Skills

**Programming:** R

**Packages:** ggplot2, dplyr, tidyr

**Statistical Skills:** Exploratory Data Analysis (EDA), Descriptive
Statistics, Data Visualization, Count Data Analysis

**Public Health Skills:** Epidemiologic Data Analysis, Interpretation
of Demographic Patterns, Public Health Research

---

## 📂 Repository Structure

    ├── README.md
    ├── code/
    │   └── substance_use_analysis.R
    ├── figures/
    │   ├── drug_distribution.png
    │   ├── drug_use_gender.png
    │   ├── drug_use_race.png
    │   └── drug_use_school.png
    └── report/
        └── final_report.pdf

---

## 👤 Author

Graduate Student in Biostatistics

