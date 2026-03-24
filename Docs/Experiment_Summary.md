# A/B Testing Analysis — New Landing Page Experiment


## Objective
To evaluate whether a new landing page (treatment) improves user conversion rates compared to the existing landing page (control).


---


## Experiment Setup

- **Control Group**: Users exposed to the existing landing page
- **Treatment Group**: Users exposed to the new landing page
- **Metric**: Conversion Rate (binary outcome: converted vs not converted)


---


## Hypothesis

- **H0 (Null Hypothesis)**: There is no difference in conversion rate between control and treatment groups  
- **H1 (Alternative Hypothesis)**: Treatment group has a different conversion rate than control group  


---


## Data Overview

- [Kaggle Dataset](https://www.kaggle.com/datasets/zhangluyuan/ab-testing)
- Dataset contains user-level experiment data
- Key fields:
  - `group` → control vs treatment
  - `converted` → 0 (no conversion), 1 (conversion)
  - `timestamp` → event timing
- Groups are balanced, ensuring a fair comparison


---


## Key Metrics

- **Control Conversion Rate**: 12.04%
- **Treatment Conversion Rate**: 11.89%
- **Lift**: -1.23%

The treatment resulted in a lower conversion rate compared to control.


---


## Statistical Significance

**p-value**: 0.2

### Interpretation:
- p-value > 0.05  
- Result is **not statistically significant**

The observed difference could be due to random variation.


---


## Confidence Interval

- **95% Confidence Interval for difference in conversion**: ​​(-0.0038, 0.00086)

### Interpretation

- The interval includes **0**, meaning:
- The true effect could be:
  - slightly negative  
  - no effect  
  - slightly positive  

This reinforces that the result is **inconclusive**.


---


## Time-Based Analysis

Conversion trends over time show:
- No consistent improvement in treatment group
- Treatment often underperforms control across multiple days

Suggests:
- No stable positive signal from treatment
- Possible variability or weak effect


---


## Key Insights

- Treatment shows a **negative directional impact** on conversion (-1.23%)
- The result is **not statistically significant**, indicating uncertainty
- Confidence interval crossing zero confirms lack of reliable effect
- No consistent improvement trend over time
- The experiment does not provide evidence of performance improvement


---


## Recommendations

- Do not roll out the treatment, as it does not show a statistically significant improvement
- Investigate potential reasons for the negative directional impact
- Iterate on the page design and test improved variations


---


## Conclusion

The experiment does not provide evidence that the new landing page improves conversion rates.

While the result is not statistically significant, the observed negative lift and lack of consistent improvement suggest that the treatment is not a viable candidate for rollout.
