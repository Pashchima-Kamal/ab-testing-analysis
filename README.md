# A/B Testing Analysis — New Landing Page


## Overview
This project analyzes the effectiveness of a new landing page using A/B testing. The goal is to determine whether a new landing page improves conversion rates compared to the existing version.


---


## Tools Used
- Python
- pandas
- numpy
- statsmodels
- matplotlib
- seaborn


---


## Key Features
- Conversion rate comparison between control and treatment
- Lift calculation
- Statistical significance testing (z-test)
- Confidence interval estimation
- Time-based performance analysis
- Business-focused recommendations


---


## Key Results


- Lift: **-1.23%**
- p-value: **0.2**
- Confidence Interval: **(-0.0038, 0.00086)**


---


## Key Insights


- Treatment does not improve conversion rate
- Observed impact is negative but not statistically significant
- Confidence interval includes zero, indicating uncertainty
- No consistent improvement over time


---


## Business Recommendation


The treatment should **not be rolled out**, as it does not demonstrate a statistically significant improvement and shows a negative directional trend.


---


## Project Structure


## Project Structure


```
ab_testing_analysis/
│
├── Data/
│   └── ab_testing.csv
│
├── Notebook/
│   └── ab_testing_analysis.ipynb
│
├── Docs/
│   └── experiment_report.md
│
└── README.md
```




---


## Conclusion


This project demonstrates how A/B testing can be used to make data-driven decisions and prevent ineffective or harmful changes from being deployed.