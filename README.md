# Health Survey Data on Antenatal Care Providers in Kenya
## NON-TECHNICAL CONTENT
1. **Presentation [Link](https://docs.google.com/presentation/d/1zokURQf_vM1NNQa6K9JbogbgCE6KJFPQqSFZlEUbfDk/edit?usp=sharing)**
2. **Tableu [link](https://public.tableau.com/app/profile/ian.moire/viz/AntenatalCareAccessInsights/AntenatalCareAccessInsights)**

## Background
The dataset originates from demographic and health surveys conducted in Kenya, focusing on healthcare service delivery, preferences, and outcomes over several decades. It includes data on indicators such as antenatal care providers, treatment of specific conditions, and the number of children born. The information is vital for understanding healthcare trends, resource allocation, and service quality across different regions and timeframes in Kenya.

## Objectives
1. **Examine trends and patterns in healthcare service delivery in Kenya.**

2. **Analyze resource efficiency and service preferences.**

3. **Identify gaps in healthcare provision to inform policymaking and resource optimization.**

## Research Questions
1. **How does the utilization of different types of antenatal care providers (e.g., doctors vs. nurses/midwives) vary across different regions in Kenya and over time?**
2.  **How has the percentage of women receiving antenatal care from different provider types changed from 1989 to 2022, and what factors may explain these trends?**
3.  **Are there significant geographical disparities in antenatal care provider utilization across urban and rural areas of Kenya?**
4.  **What are the perceived barriers to accessing antenatal care services among women in Kenya, and how do these barriers differ by region or socioeconomic status?**
5.  **How do the rates of antenatal care provider utilization in Kenya compare to those in other countries with similar demographic and health indicators?**

## Data Description
The dataset used in this analysis is the "access-to-health-care_national_ken dataset" from "data.humdata.org". It contains 1142 records, with features such ISO3, CountryName, DHS_CountryCode, Indicator, Value and Precision, SurveyYear and SurveyId, DenominatorWeighted, DenominatorUnweighted, Weighted_Ratio, and Preferred_Percentage. The dataset spans multiple years, offering both categorical and numerical insights, which are key for cross-sectional analysis.

## Methodology
The analysis will involve the following key steps:

1. **Data Cleaning:** Handled missing values, duplicates, outliers, and inconsitencies.

2. **Exploratory Data Analysis:** Visualized the distribution of indicators and analyzed trends across survey years.

3. **Feature Engineering:** Created new features such as Weighted_Ratio and Preferred_Percentage for deeper insights.
                            Applied transformations (e.g., logarithmic) to normalize skewed numerical data.

## Significance
The findings can guide policymakers in optimizing healthcare resource allocation and improving service delivery. Insights into service preferences can help tailor healthcare approaches to community needs so as to inform strategies for sustainable healthcare improvements.
## Summary of key findings
Nurse/midwife care providers were frequently preferred in antenatal services, while preferences for doctors varied. The analysis reveals consistent improvements in healthcare service efficiency (Weighted Ratios) over decades. The Weighted Ratios generally indicate efficient resource allocation across healthcare indicators, with consistency observed in surveys over time.

## Implications
The data indicates varying percentages of antenatal care provider utilization (doctors vs. nurses/midwives). This information can guide policymakers in allocating resources efficiently to areas with higher needs or lower usage rates, potentially improving maternal health outcomes.

## Limitations
The dataset may not capture external factors affecting antenatal care utilization, such as cultural attitudes towards healthcare, economic barriers, and geographical access to medical facilities. Depending on the sample size and methodology of the Demographic and Health Surveys (DHS), the dataset may not fully represent all segments of the population, particularly rural versus urban differences.

## Future Work
Implement predictive modeling techniques to forecast future trends in antenatal care provider usage. This could help in proactive policy formulation and resource allocation. Consider expanding the analysis to include other healthcare indicators beyond antenatal care, such as maternal morbidity and mortality rates.
## References
## ***data.humdata.org***

***(https://data.humdata.org/dataset/dhs-data-for-kenya?force_layout=desktop)***
