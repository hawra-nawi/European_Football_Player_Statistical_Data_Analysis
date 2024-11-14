## **Overview**  
This project enhances player potential insights by 50% through ANCOVA analysis, uncovering 9 significant relationships. It also improves decision-making in player management by identifying 8 key predictors for weekly wages through Logistic Regression, supported by a strong model fit. The analysis involved addressing data inconsistencies and multicollinearity, ensuring robust insights from over 500 recorded datasets, using RMarkdown.

## **Approach**  
- **Data Quality Analysis**  
- **Exploratory Data Analysis**
- **Statistical Modeling**  
  - **ANCOVA**: Assessed the impact of various variables on player potential while controlling for others.  
    - **Hypotheses**:  
      - $H_0$: No variables affect player potential.  
      - $H_1$: Variables influence player potential.  
    - **Linear Equation**:  
      $y = (4.626e+01) + (3.02e-13) \times (wage) + (6.560e-05) \times age - (5.718e-01) \times height + (6.509e-02) \times shooting + (1.085e-01) \times dribbling + (6.416e-02) \times defending + (7.931e-02) \times physics - (1.021e-01) \times \text{power long shots} + (3.154e+00) \times high.wage.indTRUE$
  - **Logistic Regression**: Analyzed factors influencing the likelihood of higher wages and potential.  
    - **Hypotheses**:  
      - $H_0$: No factors affect the likelihood of high wages.  
      - $H_1$: Factors influence high wages.  
    - **Logistic Transformation Equation**:  
      $log(\frac{p}{1-p}) = a + b_1 \times x_1 + b_2 \times x_2 + ... + b_k \times x_k$

## **Tools & Packages**  
- **Language**: R  
- **Packages**: `dplyr`, `ggplot2`, `tidyr`, `car`, `MASS`

## **Documentation**  
Access the document in [RMarkdown](https://github.com/hawra-nawi/Statistical-Modelling-of-Factors-Influencing-European-Football-Players-Potential-and-Wages/blob/main/Data%20Analysis%20and%20Statistical%20Modelling.Rmd), [HTML](https://github.com/hawra-nawi/Statistical-Modelling-of-Factors-Influencing-European-Football-Players-Potential-and-Wages/blob/main/Documentation%20Report.html), and [PDF](https://github.com/hawra-nawi/Statistical-Modelling-of-Factors-Influencing-European-Football-Players-Potential-and-Wages/blob/main/Documentation%20Report.pdf) formats.
