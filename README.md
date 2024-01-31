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

## Discussion:
Our analyses provided both expected and surprising results. In Part I, we investigated the demographics
of our patient cohort. By comparing the demographics of this cohort with the demographics reported by
the CDC for patients in New York City as a whole, we conclude that the patient populations of these four
hospitals from which our data is drawn are not in fact representative of the entire patient population of New
York City during the early days of the COVID-19 pandemic. Specifically, our patient cohort contains a larger
proportion of Black and Latino patients. Nevertheless, the ages of our patient cohort are representative of
patients in NYC as a whole. Taken together, these findings could motivate hypotheses for further study,
including (1) is the distribution of ages of residents in the communities surrounding these hospitals more
similar to the distribution of ages in all of NYC as compared to the distribution of races?, and, (2) does
SARS-CoV-2 selectively cause hospitalization-necessitating disease in older individuals, while being less or not at all selective on the basis of race? Answering these questions would require expanding the study
population beyond the hospital setting to survey individuals living in the community.

Several different comorbidities were reported among this patient cohort. Surprisingly, neither COPD nor
peripheral vascular disease were associated with patient death from COVID-19. Additionally, while dementia
alone was not associated with patient death, there was an association between all central nervous system
disorders and patient death from COVID-19.

We could not accurately represent the relationship between age and COVID-19 severity score as age was a
heavily weighted factor in calculating severity score for these patients. Rather, we investigated the effect
of race on severity score and found that there was no difference in severity score when broken down by the
five different races represented in this study (Asian, Black, Latino, White, and unknown). Unsurprisingly,
both age and severity score were higher among those who died compared to those who lived, while length
of stay in the hospital was rather evenly distributed among patients who lived and patients who died from
COVID-19.

We explored the impact of several different clinical characteristics on survival status among this cohort of
patients. First, looking at temperature, we saw no difference in body temperature between patients who
lived and died. We next investigated the measure of blood clotting, as measured by D-dimer levels, and
found that D-dimer levels were higher in patients who died from COVID-19 than those who did not die.
This finding is consistent with evidence that emerged in the first year of the pandemic that many patients
with Sars-CoV-2 were experiencing frequent clotting events such as venous thromboembolism (when a clot
forms in the venous system and dislodges to later lodge in the lungs and block blood oxygenation) and
disseminated intravascular coagulation (in which small clots form in many small blood vessels around the
body). This evidence was important for guiding the clinical standard of care, which now includes prophylatic
anticoagulation for certain populations of individuals hospitalized with SARS-CoV-2 infection [4]. Lastly,
we looked at blood pressure and found greater variance in blood pressure among those who died compared
to those who lived. This may reflect a state of physiological decompensation among these patients which
puts the patient’s life at risk. Causes of dysregulated blood pressure which may happen during SARS-
CoV-2 infection include septic shock, which occurs when the body’s immune system generates a hyperactive
response to the viral pathogen and which is life-threatening. Changes in blood pressure can also be seen
accompanying acute respiratory distress syndrome, a serious complication of COVID-19 in which the lungs
flood with fluid, and which is associated with with a high mortality rate. We were unable to accurately
predict length of stay using a suite of clinical characteristics, indicating that early strains of COVID-19 were
complex and somewhat unpredictable in their clinical impact.

## Conclusion:
We investigated clinical outcomes for 819 individuals hospitalized with COVID-19 early in the pandemic,and
found that in early 2020 COVID-19 infected people from all racial backgrounds while tending to cause more
deaths among older individuals. Of the clinical characteristics measured, blood pressure and D-dimer differed
among those who died from COVID-19 compared to those who lived, while temperature and WBC did not.
Overall, this dataset provides valuable insight into the clinical outcomes of early COVID-19 in an urban
US-based population.

## Sources:
[1] “COVID-19: Data: Trends and Totals.” Last updated December 7, 2023. https://www.nyc.gov/site/
doh/covid/covid-19-data-totals.page

[2] Altschul, David (2021). Neurologic complications of COVID-19 [Dataset]. Dryad. https://doi.org/10.
5061/dryad.7d7wm37sz

[3] “Morbidity and Mortality Weekly Report: COVID-19 Outbreak – New York City, February 29-June
1, 2020.” Centers for Disease Control and Prevention. https://www.cdc.gov/mmwr/volumes/69/wr/
mm6946a2.htm

[4] “Antithrombotic Therapy in Patients with COVID-19.” COVID-19 Treatment Guidelines. National
Institute of Health. Last updated October 10, 2023. https://www.covid19treatmentguidelines.nih.gov/
therapies/antithrombotic-therapy/
