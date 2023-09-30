# Hypothesis_test_drinking_LDL
Find Correlation between alcohol consumption and LDL Cholsterol levels

Data Gathering:

Hypothesis: The hypothesis tested in this analysis was whether there is a correlation between drinking habits and LDL cholesterol levels.
Null Hypothesis (H0): The null hypothesis stated that there is no significant correlation between drinking and LDL cholesterol levels.
Alternative Hypothesis (H1): The alternative hypothesis suggested that there is a significant correlation between drinking and LDL cholesterol levels.
A dataset containing various health-related variables, including drinking history and LDL cholesterol levels, was imported and explored.


Data Cleaning:

Missing values and duplicates were checked, and missing values were not found in the dataset. Twenty-six duplicate entries were identified and removed.
The column 'DRK_YN' was renamed to 'drinking_hist,' and its values ('Y' for Yes and 'N' for No) were replaced with numerical values (1 for Yes and 0 for No).
A subset of the dataset containing only 'total cholesterol,' 'HDL cholesterol,' 'LDL cholesterol,' and 'drinking history' columns was created.
Outliers in the 'LDL cholesterol' column were replaced with the mean value within a specified range.


Data Analysis:

The dataset contained a roughly equal distribution of individuals with drinking history (1) and without drinking history (0).
A pie chart illustrated this distribution.
The mean and standard deviation of LDL cholesterol levels were calculated for both drinkers and non-drinkers.
On average, individuals with a drinking history had slightly lower mean LDL cholesterol levels (111.33) compared to non-drinkers (114.38), with almost equal proportions of both groups.
A box plot visualized the distribution of LDL cholesterol levels for drinkers and non-drinkers.
A correlation heatmap showed that the correlation coefficient between drinking history and LDL cholesterol was -0.04, indicating a very weak negative linear relationship.
An independent two-sample t-test was conducted, resulting in a negative t-statistic (-44.55) and a p-value of 0.0. This strongly supported the rejection of the null hypothesis, indicating that drinking is associated with lower LDL cholesterol levels.


Conclusion:

The analysis suggests a significant correlation between drinking habits and lower LDL cholesterol levels. Individuals with a history of drinking tend to have slightly lower LDL cholesterol levels compared to non-drinkers.





