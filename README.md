# AB_Testing_UX_LandingPage_LunarTech_CaseStudy
AB Testing UX LandingPage LunarTech CaseStudy from the Python for Data Science *Course freecodecamp.org*
# Overview
This repository contains a case study on A/B testing focused on optimizing the UX of a landing page for LunarTech. The project walks through the entire process from hypothesis formulation to statistical analysis, with a focus on increasing the Click-Through Rate (CTR) of the landing page.

# Business Goal
The primary business objective is to increase the **Click-Through Rate (CTR)** on the LunarTech landing page. The hypothesis is that changing the design of the call-to-action (CTA) button from Green to Red will result in a higher CTR.

# Hypothesis Formulation
- **Null Hypothesis (H0):** Changing the CTA button from Green to Red does not affect the CTR.
- **Alternative Hypothesis (H1):** Changing the CTA button from Green to Red increases the CTR.

# Data Exploration
## Key Metrics
- **Primary Metric:** Click-Through Rate (CTR)
- **Secondary Metrics:** Time on Page, Bounce Rate

# Statistical Test Selection
A **two-sample Z-test** was chosen to compare the CTRs between the control (Green button) and treatment (Red button) groups.

# Calculating Test Statistics
The Z-test statistic was calculated to assess the difference in CTRs. The notebook details the steps involved:
- Total Clicks per Group
- Pooled Estimates for Clicks per Group
- Pooled Variance
- Standard Error and Test Statistics

# Calculating P-Value and Statistical Significance
The P-value was computed to determine if the observed difference in CTRs is statistically significant. A significance level (𝛼) of 0.05 was used.

# Significance and Confidence Interval (CI)
- **P-value:** Calculated from the **Z-test**
- **95% Confidence Interval:** Range calculated for the difference in CTRs
If the P-value is less than 0.05, the null hypothesis is rejected, indicating a statistically significant difference between the two groups.

# Practical Significance
Beyond statistical significance, the effect size and practical significance were evaluated to determine whether the observed difference is meaningful for the business.


Here’s an updated conclusion section for your README file, incorporating the points about statistical significance, confidence intervals, and practical significance:

# Conclusion
The A/B test conducted on the LunarTech landing page revealed the following insights:

**Statistical Significance:** There exists a statistically significant difference in the Click-Through Rate (CTR) between the experimental version (with the "Enroll Now" button) and the control version (with the "Secure Free Trial" button) at a 5% significance level. This indicates that the change in the CTA button has a meaningful impact on user behavior.

**Confidence Interval:** The confidence interval for the difference in CTRs is quite narrow, providing a precise estimate of the effect size. This narrow confidence interval further strengthens the reliability of the results.

**Practical Significance:** In addition to statistical significance, there is practical significance in the difference between the experimental and control versions at a 10% Minimum Detectable Effect (MDE). The results suggest that the observed difference in CTR is not only statistically significant but also practically meaningful, with potential implications for increasing user engagement and conversions.

These findings suggest that implementing the "Enroll Now" button could lead to a measurable improvement in CTR, making it a recommended change for LunarTech's landing page.
