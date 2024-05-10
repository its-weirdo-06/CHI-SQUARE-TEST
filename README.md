# Chi-Square Test for Association between Device Type and Customer Satisfaction
## Description:

This Python script performs a Chi-Square Test to determine if there is a significant association between the type of smart home device purchased (Smart Thermostats vs. Smart Lights) and the customer satisfaction level.

## Background:

Mizzare Corporation has collected data on customer satisfaction levels for two types of smart home devices: Smart Thermostats and Smart Lights. They want to determine if there's a significant association between the type of device purchased and the customer's satisfaction level.

## Data Provided:
The data is summarized in a contingency table showing the counts of customers in each satisfaction level for both types of devices:

| Satisfaction      | Smart Thermostat | Smart Light | Total |
|-------------------|------------------|-------------|-------|
| Very Satisfied    | 50               | 70          | 120   |
| Satisfied         | 80               | 100         | 180   |
| Neutral           | 60               | 90          | 150   |
| Unsatisfied       | 30               | 50          | 80    |
| Very Unsatisfied  | 20               | 50          | 70    |
| **Total**         | **240**          | **360**     | **600** |

## Objective:

To use the Chi-Square test for independence to determine if there's a significant association between the type of smart home device purchased (Smart Thermostats vs. Smart Lights) and the customer satisfaction level.

## Assignment Tasks:

1. State the Hypotheses:
   
2. Compute the Chi-Square Statistic:
   
3. Determine the Critical Value:
Using the significance level (alpha) of 0.05 and the degrees of freedom (which is the number of categories minus 1)

4. Make a Decision:
Compare the Chi-Square statistic with the critical value to decide whether to reject the null hypothesis

## Key Findings and Insights:

- **Chi-Square Statistic:** The calculated Chi-Square Statistic value is 5.638227513227513.
  
- **Degrees of Freedom:** The degrees of freedom for the test are 4.
  
- **Critical Value:** The critical value at a significance level of 0.05 is 9.487729036781154.
  
- **Decision:** Based on comparing the Chi-Square Statistic and the Critical Value, the decision is to Fail to reject the null hypothesis.
  
- **Conclusion:** Consequently, the conclusion drawn from the test is that there is no significant association between the type of smart home device and customer satisfaction level.

## Further Analysis:

- Consider conducting additional statistical tests or exploring other factors influencing customer satisfaction.
  
- Explore the impact of different variables on customer satisfaction through regression analysis or predictive modeling.
