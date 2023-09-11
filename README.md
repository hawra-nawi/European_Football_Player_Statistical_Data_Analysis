# ****European Football Player - Statistical Data Analysis (R)****

## **Project Overview**

- **Objective:** This project aims to conduct a comprehensive statistical analysis of European Football Player data, emphasizing data quality analysis, exploratory data analysis (EDA), and statistical modeling.
- The analysis provides insights into factors influencing a player's potential and their likelihood of earning a weekly wage above 8000 Euro.
- Key statistical analysis include:
    - **ANCOVA Analysis:** Assessing factors influencing a player's potential.
    - **Logistic Regression Analysis:** Investigating factors affecting a player's likelihood to earn a high weekly wage.
- R libraries used: dplyr, ggplot2, gridExtra, grid, corrplot, reshape2.
- Access the document in RMarkdown, HTML, and PDF formats.

## **Data Quality Analysis (Section #1)**

- **Objective:** Ensure data accuracy, consistency, and reliability.
- Key steps:
    - Data summary
    - Identifying numerical and categorical variables
    - Handling outliers
    - Addressing missing data
    - Visualizing data anomalies

### **Examples of Data Cleaning**

![The Before and After Cleaning Process for Pace.png](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Data%20Analysis%20Section/The%20Before%20and%20After%20Cleaning%20Process%20for%20Pace.png)

![The Before and After Cleaning Process for Preferred Foot.png](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Data%20Analysis%20Section/The%20Before%20and%20After%20Cleaning%20Process%20for%20Preferred%20Foot.png)

## **Exploratory Data Analysis (EDA) (Section #2)**

- **Objective:** Summarise dataset characteristics through visualisations.
- Visualisations include histograms, box plots, heatmaps, and hypothesis testing (Shapiro-Wilk normality test and Pearson's correlation coefficient).
- The heatmap illustrates correlations between attributes.

![Heatmap.png](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/EDA%20Section/Heatmap.png)

## **Statistical Modeling (Section #3 and #4)**

- **Objective:** Address two research questions.

### **ANCOVA Analysis: "What factors influence a football player's potential?"**

- ANCOVA tests variables affecting player potential.
- Hypotheses:
    - $H_0$: No variables affect player potentials.
    - $H_1$: Variables influence player potentials.
- Linear equation:
    - $y = (4.626e+01) + (3.02e-13) \times (wage) + (6.560e-05) \times age - (5.718e-01) \times height + (6.509e-02) \times shooting + (1.085e-01) \times (2.769e-01) \times dribbling (6.416e-02) \times defending + (7.931e-02) \times physics - (1.021e-01) \times **`power long shots`** + (3.154e+00) \times high.wage.indTRUE

### Diagnosis Plots

![Diagnosis 1-Residual vs Fitted.png](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Statistical%20Modelling/ANCOVA/Diagnosis%201-Residual%20vs%20Fitted.png)

![Diagnosis 2-quantile-quantile (Q-Q).png](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Statistical%20Modelling/ANCOVA/Diagnosis%202-quantile-quantile%20(Q-Q).png)

- Conclusion: The alternative hypothesis is accepted, but this model needs improvement due to inconsistency and multicollinearity.

### **Logistic Regression: "What factors affect the likelihood of a football player earning a weekly wage above 8000 Euro?"**

- Logistic Regression models factors influencing a player's likelihood to earn a high wage.
- Hypotheses:
    - $H_0$: No factors affect the likelihood of high wages.
    - $H_1$: Factors influence high wages.
- Logistic transformation equation:
    - $log(\frac{p}{1-p})=a + b1 \times x1 + b2 \times x2 ....bk \times xk$

### Diagnostic Measures

### Diagnostic Measures
[model](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Statistical%20Modelling/Logistic%20Regression/Model.png)

![odd ratio](https://github.com/hawra-nawi/Football-European-Players-QDA/blob/main/Images/Statistical%20Modelling/Logistic%20Regression/odd%20ratio.png)

- Conclusion: The Null Hypothesis is rejected, and the minimal adequate model is a good fit.

**Conclusion:**

- In conclusion, this project underscores the significance of data quality, exploratory data analysis, and statistical modeling in extracting valuable insights from European football player data.
- By following these analytical steps, the report ensures reproducibility and provides valuable insights into the world of football statistics.
- These findings can be invaluable for clubs, analysts, and enthusiasts looking to understand the factors influencing a player's potential and earnings in the dynamic world of European football.
