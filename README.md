# Student Success Analysis

This project analyzes the influence of financial, demographic, and macroeconomic factors on student academic performance and retention rates. The goal is to uncover actionable insights to enhance academic outcomes through data-driven strategies.

## Dashboard
The dashboard provides insights into academic performance and financial factors:

![Dashboard Screenshot]((https://github.com/SairaBatool010/Student_Success_Analysis_Dashboard/blob/main/Dashboard_Images/D2.png)
![Dashboard Screenshot]((https://github.com/SairaBatool010/Student_Success_Analysis_Dashboard/blob/main/Dashboard_Images/D1.png)
![Dashboard Screenshot]((https://github.com/SairaBatool010/Student_Success_Analysis_Dashboard/blob/main/Dashboard_Images/D3.png)

![Dashboard Screenshot]((https://github.com/SairaBatool010/Student_Success_Analysis_Dashboard/blob/main/Dashboard_Images/D4.png)


## Business Problem
The aim is to identify financial indicators (e.g., scholarship status, debt levels, parental income) and macroeconomic conditions (e.g., GDP, unemployment rates) that correlate with metrics such as grades, course completion rates, and dropout rates.

## Data Cleaning/Wrangling
- **Missing Values**:
  - `Age at Enrollment`: 2 missing values replaced with the mean.
  - `Course Name`, `Daytime/Evening Attendance`, `Nationality Name`: Fixed via mapping.
- Standardized inconsistent values (e.g., "girl" replaced with "female").
- Removed 11 duplicate rows.
- Cleaned data exported as a new CSV file.

[Python Notebook - Data Cleaning](https://colab.research.google.com/drive/12FBE2r0xjHamOoc-Qq_tryNPZPqAWxMS?usp=sharing)

## Exploratory Data Analysis (EDA)
### Univariate Analysis
[Collab Link](https://colab.research.google.com/drive/1ww47nYzSm99LZZrlEmHEfjCbzEUWwblg?usp=sharing)

### Bivariate/Multivariate Analysis
[Python File Link](https://colab.research.google.com/drive/1K5_dpozy8CII_SWVg5CRQ8bt64sfqWUZ?usp=sharing)

#### Key Findings:
- Strong correlation between first-semester and second-semester grades.
- Weak correlation between GDP and inflation rate.

## ANOVA Results
Significant findings (p < 0.05):
- **Course vs. Marital Status**: F=2.747, p=0.017
- **Daytime/Evening Attendance vs. Curricular Units (2nd Semester Approved)**: F=5.160, p=0.023
- **Scholarship Holder vs. Inflation Rate**: F=3.865, p=0.049

## Recommendations and Insights
1. Tailored support for displaced students and those with special needs.
2. Enhanced financial aid to reduce dropout rates.
3. Strategies to address gender-based differences in academic performance.

## Dashboard
The dashboard provides a comprehensive overview of academic performance, demographics, and financial factors affecting success.
