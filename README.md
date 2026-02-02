# da-task-11
# Hypothesis-Testing-in-Python

Dataset Name: Marketing A/B Testing Dataset

Tools & Libraries

Python

Google Colab

pandas

numpy

scipy

matplotlib

seaborn


A/B Testing Methodology
1️ Data Loading & Group Identification

Loaded the dataset using pandas.read_csv()

Identified control (psa) and test (ad) groups

Verified group sizes and data types

2️ Hypothesis Definition

Null Hypothesis (H0):
There is no difference in conversion rates between the control and test groups.

Alternative Hypothesis (H1):
There is a significant difference in conversion rates between the two groups.

Significance Level (α): 0.05

3️ Metric Calculation

Calculated conversion rates for both control and test groups

Compared baseline performance before testing

4️ Statistical Test Selection

Metric type: Binary (conversion: 0/1)

Test used: Independent two-sample t-test

5️ Hypothesis Testing

Computed t-statistic and p-value

Evaluated statistical significance based on α = 0.05

6️ Confidence Interval Estimation

Calculated a 95% confidence interval for the difference in conversion rates

Used the interval to validate the hypothesis test result

7️ Visualization

Bar chart comparing conversion rates of control vs test groups

Distribution plots to visualize outcome differences

8️ Business Interpretation

Translated statistical findings into actionable business insights

Provided a clear recommendation on whether to roll out the advertisement
