Student Success Analysis

Business Problem:

To enhance academic results and retention rates, the aim is to fully understand the influence of various financial factors on student success. The goal is to identify which financial indicators (e.g., scholarship status, debt levels, parental income, and employment status) and macroeconomic conditions (e.g., GDP, unemployment rates) most significantly correlate with academic performance metrics such as grades, course completion rates, and dropout rates.

Data Cleaning/Wrangling:

We tested the data for missing values. These were the values missing:

Missing values:

Age at enrollment (2)

Course Name (2)

Daytime/Evening Attendance (3)

Nationality Name (11)

For the last three, we fixed them through mapping. For "Age at Enrollment," we computed the mean and inserted it.

Python notebook link: Data Cleaning Notebook

Additional steps:

Replaced "girl" with "female" in the gender column.

Found 11 duplicated rows and removed them.

Generated a new CSV file with updated results.

EDA:

Univariate Analysis:

Collab link: Univariate Analysis Notebook

Bivariate/Multivariate Analysis:

Python file link: Bivariate Analysis Notebook

Results from Pearson’s Coefficient:

Correlation Heatmap:

Strong correlation between:

Circular results first semester and circular results second semester grades.

Weak correlation between:

GDP and inflation rate.

Application order and age at enrollment.

Course and GDP.

Course and curricular units for 1st and 2nd semester.

Visualizations:

Scatterplots and boxplots for multiple variables (refer to the Python file).

Significant ANOVA Results:

Below are the ANOVA results with p-value < 0.05:

Course and Marital Status: F-statistic = 2.747, P-value = 0.017.

Curricular units (2nd semester, approved) and Daytime/Evening Attendance: F-statistic = 5.160, P-value = 0.023.

Curricular units (2nd semester, evaluations) and Nationality Name: F-statistic = 1.628, P-value = 0.038.

Curricular units (1st semester, enrolled) and Mother's Qualification: F-statistic = 2.079, P-value = 0.019.

Course and Mother's Occupation: F-statistic = 1.924, P-value = 0.015.

Curricular units (2nd semester, enrolled) and Displaced Status: F-statistic = 6.590, P-value = 0.010.

Inflation Rate and Scholarship Holder Status: F-statistic = 3.865, P-value = 0.049.

GDP and Scholarship Holder Status: F-statistic = 6.099, P-value = 0.014.

For full results, refer to the notebooks linked above.

Recommendations and Insights:

Course and Demographic Factors:

Marital Status: Significant differences in course distribution suggest marital status influences course enrollment choices.

Mother's Occupation: Variations in course enrollment highlight a socio-economic dimension in course selection.

Gender: Strong gender-based differences in course selection suggest societal norms or career aspirations play a role.

Curricular Performance and Attendance Type:

Daytime/Evening Attendance: Attendance type affects student performance significantly.

Displaced Students: Displacement status correlates with performance, indicating challenges or advantages linked to mobility.

Socio-Economic Factors and Academic Outcomes:

Educational Special Needs: Tailored support is required as these students show different academic outcomes.

Debtor Status: Financial stress may contribute to varying academic performances.

Economic Indicators and Student Characteristics:

Scholarship Holder Status: Macroeconomic conditions influence the likelihood of receiving scholarships.

Displacement and Economic Factors: Economic conditions like unemployment and GDP strongly impact student mobility.

Admission and Previous Academic Performance:

International Students: These students display distinct academic profiles compared to domestic students.

Marital Status: Married students may have different academic backgrounds and outcomes.

Application Mode and Student Attributes:

Application Mode: The mode of application is associated with distinct academic characteristics.

Gender Differences: Substantial gender-based differences in academic performance metrics are evident.

Parental Influence on Academic Outcomes:

Mother's and Father's Qualifications: Parental education significantly impacts student success.

Dashboard:

Dashboard Screenshot:

The dashboard provides an overview of key insights, including:

Scorecards for grades and student performance metrics.

Slicers for analyzing different demographics.

Insights showing:

Scholarship holders are less likely to drop out.

Single students have higher graduation rates.

Financial stability significantly impacts student outcomes.

The dashboard effectively identifies critical factors affecting student success.
