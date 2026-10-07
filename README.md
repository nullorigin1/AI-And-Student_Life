# Artificial Intelligence and Student Life: A Statistical Study of Its Influence on Learning, Behaviour and Social Life

## Overview

This project studies the use of AI tools (ChatGPT, Google Gemini, Microsoft Copilot and others) among school students in Vadodara. It examines how AI use relates to academic performance, cognitive development, emotional well-being, social behaviour and overall student life. Primary data from 340 students in 10 schools was collected with a structured questionnaire and analysed using descriptive and inferential statistics.

## Objectives

- Assess the positive role of AI in students' academic and personal lives
- Examine how AI tools support cognitive, academic and skill development
- Identify commonly used AI platforms and their beneficial applications
- Investigate negative effects such as over-dependence, anxiety and sleep disruption
- Analyse behavioural and social risks, including reduced face-to-face interaction
- Explore the overall influence of AI on students' academic, psychological, social and behavioural development

## Methodology

**1. Pilot study**
- 30 students selected by Simple Random Sampling
- Used to validate the questionnaire and estimate the proportion of regular AI users (p = 0.33)

**2. Sample size**
- Cochran's formula at 95% confidence and 5% margin of error: n = 339.78 ≈ **340**

**3. Sampling**
- Population: school students (9th–12th standard) across 250 schools in 7 zones of Vadodara; 3,882 students in the 10 selected schools
- Multistage design: random cluster sampling of schools (proportional to zone size), followed by proportionate stratified sampling of students within each school

| Zone | Schools in zone | Schools selected |
| --- | --- | --- |
| Babajipura | 45 | 2 |
| Chhani | 13 | 1 |
| Fatehpura | 29 | 1 |
| Raopura | 10 | 1 |
| Sayajigunj | 71 | 2 |
| Wadi | 44 | 2 |
| Sheher | 38 | 1 |
| **Total** | **250** | **10** |

**4. Questionnaire design and validation**
- 50 questions in 6 sections: demographics, AI usage and platforms, positive impacts, negative impacts, behavioural and social patterns, and parental perspectives
- Administered on paper and through Google Forms
- Reliability checked with Cronbach's Alpha: positive impact scale α = 0.776, negative impact scale α = 0.751, overall α = 0.825

**5. Statistical analysis**
- Respondents: 340 in total, of whom 303 (89.1%) were AI users and formed the analysis sample for the impact scales
- Normality checked with the Shapiro-Wilk test, so parametric tests were paired with non-parametric alternatives:
  - One-sample t-test and Wilcoxon Signed-Rank test against the scale midpoint of 3, with Cohen's d and 95% confidence intervals
  - Chi-Square Goodness-of-Fit test for platform usage
  - One-Way ANOVA and Kruskal-Wallis test for group comparisons
  - Pearson correlation and multiple linear regression
  - Net Impact Score combining the positive and negative scales
- Bar charts, histograms, heatmap, gauge and radar charts for visualisation

## Key Findings

- **Adoption:** 89.1% of respondents (303 of 340) use AI tools. ChatGPT (55.8%) and Google Gemini (48.8%) are the most used platforms, and academic use is the main purpose (87.0%).
- **Positive impact:** The mean Positive Impact Score of 3.257 is significantly above neutral (t(302) = 6.484, p < 0.001, d = 0.373). Problem-solving, academic understanding and independent learning are the highest-rated benefits.
- **Negative impact:** The mean Negative Impact Score of 2.667 is significantly below neutral (t(302) = −8.842, p < 0.001, d = −0.508). Procrastination and less satisfying human conversations are the most-endorsed concerns.
- **Platforms:** Usage is significantly uneven across ChatGPT, Gemini and Copilot (χ²(2) = 36.32, p < 0.001).
- **Usage frequency:** Frequency of use is not related to the positive score (r = −0.037, p = 0.602). It shows a small but significant association with the negative score (r = 0.184, p < 0.01).
- **Behavioural risk:** Negative scores differ significantly by comfort in talking to AI (H(2) = 10.59, p = 0.005) and by reported change in sleep quality (H(2) = 44.84, p < 0.001). Gender and academic level show no significant effect.
- **Overall:** The Net Impact Score is −1.90%, in the neutral range. A regression of the positive score on usage frequency, daily time and negative score explains 0.72% of the variance. These are associations in self-reported data, not evidence of causation.

## Tools

Google Forms, paper questionnaire, statistical softwares, Python, R


## Team

Palak Kumawat,  Jamil Mahida, Krupa Valand, Priyanshi Gandhi

**Guide:** Prof. Murlidharan Kunnumal

## Acknowledgements

Thanks to Prof. Murlidharan Kunnumal for his guidance throughout the project, and to the Department of Statistics, MSU Baroda, for providing the academic environment and resources for this research.
