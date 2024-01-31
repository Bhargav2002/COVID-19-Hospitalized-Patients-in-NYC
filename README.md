# Contributors
 1. Anna Kolstad - akolstad@alumni.princeton.edu
 2. Bhargav Sai Bhuvanagiri - bbhuvana@ur.rochester.edu
 3. Jacob Crossett - jrcrossett22@gmail.com
 4. Natalie Vance - natalievance95@gmail.com

# COVID-19-Hospitalized-Patients-in-NYC
## Intoduction:
SARS-CoV-2 infection swept through New York City in early 2020 and has caused over 219,000 hospitalizations and over 45,000 deaths in the city since [1]. In this project, we examine a dataset published by David Altschul from Montefiore Medical Center that characterizes hospitalization and death in the early days of the pandemic in four hospitals in New York City and Westchester County, among patients admitted to the hospital between March 1 and April 16, 2020 due to SARS-CoV-2 infection [2]. In total, this dataset describes 4711 patients across 84 variables, including patient demographic information, clinical presentation, medical history, clinical test results, and patient survival. From this dataset, we investigated clinical outcomes for 819 individuals hospitalized with COVID-19 early in the pandemic. We split this work into three different parts, first exploring the dataset and distributions of the variables we sought to use throughout the analysis. Second, we examined the survival status of the COVID-19 patients in this cohort. Lastly, we performed several inferential statistical tests to parse out which clinical measures are most useful in analyzing and predicting COVID-19 patient outcomes.
## Methods:
We restricted our analysis to only those patients for whom all 84 variables were recorded and for which feasible values existed for each variable. For example, we removed all patients from the dataset with negative values recorded for body temperature. After cleaning the data in this manner, we were left with 819 individual patients.
