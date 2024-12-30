# Analyzing the Effects of Student Spending on Academic Performance

## Overview
This research project examines the causal relationship between per-pupil spending and student academic performance in California high schools, with a particular focus on students from low socioeconomic status (SES) backgrounds. The study leverages California's Local Control Funding Formula (LCFF) implementation in 2013-2014, which provides additional funding to schools with high-need student populations.

## Research Context
- **Policy Background**: Schools receive extra funding (Concentration Grant) when their high-need student population exceeds 55% of enrollment
- **Focus Areas**: English Language Arts (ELA) and Math performance
- **Time Period**: 2014-2015 academic year
- **Location**: California high schools

## Data Sources
- California Assessment of Student Performance and Progress (CAASPP) results
- Census Day Enrollment Data
- Current Expense of Education data
- California Basic Educational Data System (CBEDS)

## Methodology
The study employs a Regression Discontinuity Design (RDD) to analyze the impact of additional funding:
1. Analysis without covariates (5% bandwidth around 55% threshold)
2. Analysis controlling for school spending per Average Daily Attendance (ADA) (10% bandwidth)

## Key Findings
- No statistically significant impact of additional funding on ELA scores
- No significant effect on Math scores at the treatment threshold
- When controlling for spending per ADA:
  - ELA scores showed no significant relationship with spending
  - Math scores showed a small negative correlation with per-student spending
  - Both models had low explanatory power (R² values < 0.04)

## Limitations
- Spending data available only at district level, not school level
- Temporal gaps between policy implementation and available data
- Limited availability of control variables
- Dataset misalignment due to different collection years
- Sample size reduction due to data cleaning

## Conclusions
The study found that increased funding alone did not lead to statistically significant improvements in student performance. This suggests that:
- Simply increasing financial resources may not automatically translate to better academic outcomes
- More research is needed on how funds are allocated and utilized
- Future studies should consider broader outcome measures and longitudinal approaches

## Authors
Isamar Marte Nunez, Duru I. Unsal, and Jackline W. Wambua  
Stanford University  
ECON 115: Causality, Decision Making, and Data Science  
Professor Guido Imbens and Professor Mary Wooters
