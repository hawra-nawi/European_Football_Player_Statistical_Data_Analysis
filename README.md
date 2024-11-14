## **Overview**  
This project analyzes the factors influencing European football players' potential and wages using statistical modeling techniques such as ANCOVA and Logistic Regression. Key insights were gained on how factors like performance, age, weight, and height influence player outcomes.

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
Access the document in RMarkdown, HTML, and PDF formats.
