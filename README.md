# Antibiotic Usage Analysis

**Table of Contents**

**Project Overview**

This data analysis project aims to provide insights into the antibiotic usage in a hospital set up. The dataset focuses on the different aspects of antibiotics and their indications. The dataset contains age and gender of the patient, diagnosis of the patient, Antibiotics used to treat patient Dosage of the antibiotics in grams Route of application of antibiotics Frequency of usage of antibiotics Duration of treatment using antibiotics in days Indication of antibiotics. By analyzing the various aspects of antibiotic usage, we seek to identify trends, come up with data driven recommendations and gain a deeper understanding of antibiotic usage in hospitals.

**Data Sources**

The primary dataset used for this analysis is the “Antibiotic usage.csv” file.
The data was obtained by group of medical students in Myanmar, Mandalay who were researching on antibiotics usage in hospitals.

**Tools**

Python: Data cleaning, analysis and creating reports

**Data cleaning/Preparation**

In the initial data preparation process the following tasks were performed:
Data loading and inspection
Handling-missing values
Data cleaning and formatting

**Explanatory Data Analysis**

It involved exploring the antibiotic usage data and answering key questions such as:
What is the overall antibiotic trend?
Which is the most prescribed antibiotic?
Which antibiotics are mostly prescribed for particular indications?
What is the correlation between antibiotic prescribed, routes of administration and frequency of administration.

**Data Analysis**

Includes python code features

```Python

df['Frequency'].value_counts()

```

**Results/Findings**

Ceftriaxone is the most prescribed antibiotic.
The intravenous route of drug administration has the highest correlation with the twice daily dosing frequency.
Metronidazole is the mostly used antibiotic in patients with aspiration pneumonia.

**Recommendations**

Prescribers should recommend oral antibiotics for less complicated infections where the patient is in a position to tolerate oral medication.
Prescribers should consider other beta-lactums when prescribing to reduce the over-prescribing of ceftriaxone.
Implement strict treatment guidelines to tackle over-prescribing of antibiotics.

**Limitations**

I had to put all the antibiotics having the same active ingredient under one name because they would have affected the accuracy of my conclusions from the analysis.

**References**

Sutradhar, K. B., Saha, A., Huda, N. H., & Uddin, R. (2014). Irrational use of antibiotics and antibiotic resistance in southern rural Bangladesh: perspectives from both the physicians and patients. Annual Research & Review in Biology, 4(9), 1421-1430.

Ferdous, J., Sachi, S., Al Noman, Z., Hussani, S. A. K., Sarker, Y. A., & Sikder, M. H. (2019). Assessing farmers’ perspective on antibiotic usage and management practices in small-scale layer farms of Mymensingh district, Bangladesh. Veterinary world, 12(9), 1441.





