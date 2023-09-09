# Football-European-Players-QDA

This repository presents a comprehensive analysis of European football player data, demonstrating the best practices for documenting a quantitative analysis. The analysis is structured into three main sections:

1. Data Quality Analysis (Section #1)
2. Exploratory Data Analysis (EDA) (Section #2)
3. Statistical Modelling (Section #3 and #4)

The table below is the metadata of the ['European Football Players'](https://github.com/hawra-nawi/Football-European-Players-QDA/tree/main/Data):

| Column Name | Column Description |
| --- | --- |
| sofifa_id | Player ID code |
| potential | player potential overall attribute – measured on a scale 0-100 |
| wage_eur | weekly player wage in Eur |
| age | player age |
| height_cm | Player height in cm |
| weight_kg | Player weight in Kg |
| club_name | Name of the player’s club |
| preferred_foot | player preferred foot |
| pace | player pace attribute – measured on a scale 0-100 |
| shooting | player shooting attribute– measured on a scale 0-100 |
| passing | player passing attribute– measured on a scale 0-100 |
| dribbling | player dribbling attribute– measured on a scale 0-100 |
| defending | player defending attribute– measured on a scale 0-100 |
| physic | player physic attribute– measured on a scale 0-100 |
| power_strength | player strength attribute– measured on a scale 0-100 |
| power_long_shots | player long shots attribute– measured on a scale 0-100 |
| high.wage.ind | Binary variable based on weekly wage - Is weekly wage above 8000 Euro |

1. **Data Quality Analysis (Section #1)**: Ensuring data accuracy, consistency, and reliability is crucial for meaningful analysis. This section covers data summary, identifying numerical and categorical variables, handling outliers, addressing missing data, and visualizing data anomalies.

2. **Exploratory Data Analysis (EDA) (Section #2)**: EDA involves summarizing dataset characteristics through visualizations. Various visualizations are used, including histograms, boxplots, heatmap and hypothesis testing, to uncover insights about player attributes, distribution, and relationships.

3. **Statistical Modeling (Section #3 and #4)**: This section delves into statistical modeling, addressing two research questions. Firstly, it explores the factors influencing a football player's potential using ANCOVA analysis. Secondly, it investigates the factors affecting a player's likelihood to earn a weekly wage above 8000 Euro using Logistic Regression. Both analyses yield valuable insights, though improvements are suggested for the latter model.

This project exemplifies the importance of data quality, exploratory data analysis, and statistical modeling in extracting meaningful insights from European football player data. By following these analytical steps, the report ensures reproducibility and provides valuable insights into the world of football statistics.
