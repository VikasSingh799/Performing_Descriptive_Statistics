# Performing Descriptive Statistics with Python
# Objective of this project
1. A statistics test was conducted for 10 learners in a class. The mean of their score is 85 and the variance of the score is zero. What can you interpret about the score obtained by all learners?

2. In a residential locality, the mean size of the house is 2224 square feet and the median value of the house is 1500 square feet. What can you interpret about the skewness in the distribution of
house size? Are there bigger or smaller houses in the residential locality?

3. The following table shows the mean and variance of the expenditure for two groups of people. You want to compare the variability in expenditure for both groups with respect to their mean. Which statistical measure would you use to evaluate the variability in expenditure? Please provide an explanation for your answer.
| Expenditure | Group I  | Group II |
|-------------|----------|----------|
| Mean        | $500,000 | $40,000  |
| Std. Dev.   | $125,000 | $10,000  |

4. During the survey, the ages of 80 patients infected by COVID and admitted to one of the city hospitals were recorded and the collected data is represented in the less than cumulative frequency distribution table.
| Age (in yrs.) | No. of Patients |
|---------------|-----------------|
| 5 - 15        | 6               |
| 15 - 25       | 11              |
| 25 - 35       | 21              |
| 35 - 45       | 23              |
| 45 - 55       | 14              |
| 55 - 65       | 5               |

a. Which class interval has the highest frequency?
b. Which age was affected the least?
c. How many patients aged 45 years and above were admitted?
d. Which is the modal class interval in the above dataset
e. What is the median class interval of age?

5. Assume you are the trader and you have invested over the years, and you are worried about the average return on investment. What average method would you use to compute the average return for the data given below?
| Year | Return | Asset Price |
|------|--------|-------------|
| 2015 | 36%    | 5000        |
| 2016 | 23%    | 6400        |
| 2017 | -48%   | 7890        |
| 2018 | 30%    | 9023        |
| 2019 | 15%    | 4567        |
| 2020 | 31%    | 3890        |

6. Suppose you have been told to measure the average height of all the males on the earth. What would be your strategy for the same? Would the average height be a parameter or a statistic? Justify your answer.

7. Calculate the z score of the following numbers:
X = [4.5,6.2,7.3,9.1,10.4,11]

# Here we have a dataset, Bank Personal Loan Modelling.csv. Now we have give output from this dataset

8. Give us the statistical summary for all the variables in the dataset.
9. Evaluate the measures of central tendency and measures of dispersion for all the quantitative variables in the dataset.
10. What statistical method will you use to examine the presence of a linear relationship between age and experience variables? Also, create a plot to illustrate this relationship.
11. What is the most frequent family size observed in this dataset?
12. What is the percentage of variation you can observe in the ‘Income’ variable?
13. The ‘Mortgage’ variable has a lot of zeroes. Impute with some business logical value that you feel fit for the data.
14. Plot a density curve of the CCAvg variable for the customers who possess credit cards and write an interpretation about its distribution.
15. Do you see any outliers in the dataset? If yes, what plot you would think will be suitable to showcase to the stakeholders?
16. Give us the decile values of the variable ‘Income’ in the dataset.
17. Give the IQR of all the variables which are quantitative and continuous.
18. Do the higher-income holders spend more on credit cards?
19. How many customers use online banking? Do customers using bank internet facilities have higher incomes?
20. Using the z-score of the income variable, find out the number of observations outside the +-3σ.
# Findings/Suggestions
1. The mean of the scores is 85, which is the average score.Variance = 0 means no variation in the data, and all values are identical. Therefore, all learners scored 85 in the test.
2. When the mean is greater than the median, the distribution is typically right-skewed or positively skewed. In a right-skewed distribution, most houses are smaller, but there are a few much larger houses that pull the mean up or higher.The majority of houses are smaller : Since the median size is 1500 square feet, it means that more than the half of the houses in the area are smaller than this size. So, many houses are around or below 1500 square feet. Here the median represents the middle value.Higher mean due to larger houses : The mean size of 2224 square feet is higher than the median. This means that there are some significantly larger houses in the area that are larger than 2224 square feet. These big houses are skewing the average upwards (increase the average size of all the houses), making the mean higher than the median
3. In my Opinion, the Coefficient of Variation (CV) is the best statistical measure to compare the relative variability in expenditure between the two groups with respect to their mean. CV expresses variability as a percentage, making it easier to interpret how much variation exists in relation to the average value, rather than just looking at raw variance. CV is not affected by the magnitude of the mean, making it more effective for comparing datasets with different means. Since we have both the mean and variance, CV provides a clear way to analyze which group has more variability in spending relative to their mean.
Calculating CV:
The CV is calculated using the formula : 𝐶𝑉=(Standard Deviation/Mean)×100
CV for Group I : 𝐶𝑉=(125,000/500,000)×100=25%
CV for Group II : 𝐶𝑉=(10,000/40,000)×100=25%
Conclusion : Both Group I and Group II have a Coefficient of Variation of 25% suggests that, Even though the absolute amounts of expenditure and variability are different (Group I has larger figures), the relative uncertainty or risk in expenditures is the same for both groups. This allows us to conclude that while one group spends more on average, the variability in spending behavior is consistent across both groups.This information can be crucial for budgeting, forecasting, and assessing/analyzing risk.
4. a. Which class interval has the highest frequency?
The class interval 35-45 years has the highest frequency with 23 patients.
b. Which age was affected the least?
The age group 55-65 years was affected the least with only 5 patients.
c. How many patients aged 45 years and above were admitted?
The patients aged 45 years and above fall into the age groups 45-55 years and 55-65 years. Summing these, we have 14 patients from 45-55 age group and 5 patients from 55-65 age group, Total 14 + 5 = 19 patients were admitted.
d. Which is the modal class interval in the above dataset
The modal class interval is the one with the highest frequency, which is 35-45 years with 23 patients .
e. What is the median class interval of age?
To find the median class interval:-By cumulative frequency, we can locate the middle value in the dataset. Here are the frequencies:
Age Interval	Frequency
5 - 15 years	6
15 - 25 years	11
25 - 35 years	21
35 - 45 years	23
45 - 55 years	14
55 - 65 years	5
Total number of patients = 6 + 11 + 21 + 23 + 14 + 5 = 80
Half of 80 is 40(it is the middle value of the dataset). Now we look for the class interval where the cumulative frequency reaches or exceeds 40.
Cumulative frequencies are:
Age Interval	Cumulative Frequency
5 - 15 years	6
15 - 25 years	6 + 11 = 17
25 - 35 years	17 + 21 = 38
35 - 45 years	38 + 23 = 61
The median class interval, where the cumulative frequency first exceeds 40, is 35-45 years. This is the class interval of age containing the median
5. In my opinion we should use the geometric mean to compute the average return on investment. This method is particularly suitable for calculating average returns over multiple periods because it accurately accounts for the compounding effects of investments, which is crucial for understanding the true performance of our investments over time.
Interpretation:
The negative geometric mean indicates that the investment has, on average, lost value over the 6-year period.
The magnitude of the geometric mean (-1.43%) suggests that the investment has experienced a moderate level of volatility, with some years experiencing significant losses (e.g., -48% and -30%).
The geometric mean is lower than the arithmetic mean (which would be around 4.50% in this case) because it takes into account the compounding effect of the returns. This highlights the importance of considering the geometric mean when evaluating investment performance over multiple periods.
6. Since it is impractical to measure the height of all males on Earth, I would use a sampling strategy:
Random Sampling:
I’d collect a representative sample from different regions, age groups, and ethnic backgrounds to cover the global diversity(For this we can connect to Health Departments, Educational institutes, Sports Organizations, etc..).
Stratified Sampling:
This approach would involve dividing the global male population into different groups (strata) such as by country, ethnicity, or age, and then sampling proportionally from each group. This ensures more accurate and fair representation of the population.
Parameter or Statistic:
Now, the result I get from the sample is a statistic because it's derived from a sample of the entire population, not the actual full population (which would make it a parameter). A parameter refers to the true average height of all males on Earth, which is usually unknown. The statistic serves as an estimate of this parameter. Therefore, the average height from the sample is used to infer the population paramete
7. X = [4.5, 6.2, 7.3, 9.1, 10.4, 11] (dataset)
Ans :- Z score = (X - μ ) / σ

here x is element of dataset X
μ is mean of dataset X
σ is standard deviation of dataset X
8. 5000 rows × 14 columnsis the size of data set. And there is no null values in the dataset. Also all columns are integer except for one and that  cloumn is having data type float.
9. Measures of Central Tendency:
          age,	Experience,	Income,	CCAvg	Mortgage, These are the numeric columns and below is there stats
mean	45.3384	20.1046	73.7742	1.937938	56.4988
median	45.0000	20.0000	64.0000	1.500000	0.0000
mode	35.0000	32.0000	44.0000	0.300000	0.0000
Measures of Dispersion:
          Age	  Experience	  Income   	CCAvg  	Mortgage
variance	131.404166	131.513962	2119.104235	3.054312	10345.697538
std_dev	11.463166	11.467954	46.033729	1.747659	101.713802
range	44.000000	46.000000	216.000000	10.000000	635.000000
IQR	20.000000	20.000000	59.000000	1.800000	101.000000
10. I have used Coefficient of variance method. Pearson's correlation coefficient - 0.994. and also used regplot to visualize the linear relation.
11. The most frequent family size observed in the dataset is: 1
12. A CV of 62.40% suggests that the standard deviation is more than half of the mean income. This indicates significant variability in income among the individuals in our dataset(indicates a diverse income range within the population).It highlights the need for deeper analysis to understand the factors contributing to this variability and can help inform strategies or policies aimed at addressing income disparities if relevant.
13. Here I have calculated the median of column, 'Mortgage' excluding Zero entries.
And than I have replace all zero values with the median value and saved it in df['Mortgage'] (I have not save this data in actual DataFrame, so it does not change my original data source).
Reason :
Here, the reason is not to use mean is because the data is skewed. And median is robust against these type of skewed Data. Also the data is numeric and continuous so there is no point to use mode here.
14. This represents the average credit card spending of customers who possess a credit card.
Right Skew: A right-skewed plot indicates that most credit card holders tend to have lower average spending (closer to 0 to 4 on the x-axis),
While fewer customers have much higher spending, extending the curve from 4 to 8.5 (outliers).
Concentration:Since the majority of the data is concentrated on the left side of the chart, it suggests that most credit card holders spend relatively low amounts on average. The long tail toward the right indicates a smaller group of customers who spend significantly more.
15. Age: The distribution of ages seems relatively symmetric with a median around 45 years old.There appear to be no outliers, indicating that all age values fall within a typical range.
Experience: Similar to Age, the distribution of experience is fairly symmetric.The median experience level is around 20 years, with all values also falling within expected ranges (no outliers).
Income: The Income distribution shows right skewness, with a median around 60-70K.There are several outliers on the higher end, indicating some individuals with significantly higher incomes than the typical range.
CCAvg: Average monthly credit card spending (CCAvg) also shows a right-skewed distribution.The bulk of data is concentrated below 2.5, but there are many outliers extending towards 10, suggesting a few individuals spend considerably more per month on their credit cards.
Mortgage: It also shows a right-skewed distribution. The majority of customers have no mortgage (as indicated by Q1, Q2, and Q3 being 0), but a few have large mortgages, with outliers extending up to 635.
16. Deciles divide the dataset into ten equal parts. Each decile represents a threshold such that a certain percentage of the individuals fall below that income level. Here, the 10th decile indicates that 10% of individuals in the dataset earn less than or equal to 22.0, while 90% earn more.
Income Distribution : The values increase progressively from the 10th decile (22.0) to the 100th decile (224.0). This indicates that income levels rise as you move up the deciles.The sharp increase between the lower deciles and higher deciles indicates the presence of higher-income individuals at the top end of the distribution, particularly visible from the 80th decile onward.
Income Inequality : The significant jump between the 90th decile (145.0) and the 100th decile (224.0) suggests that the top 10% of earners have a disproportionately high income compared to the rest. This could indicate income inequality within the dataset.
Median Income : The 50th decile (median) value of 64.0 suggests that half of the individuals in the dataset earn less than this amount, while the other half earn more. This gives a sense of the central tendency of income within the dataset.
17. Age(20): People in the dataset have ages that vary quite a bit, showing a mix of younger and older individuals.
Experience(20): There’s a wide range of work experience among the people, with some being new to the job and others having many years of experience.
Income (59): The incomes of the people differ a lot, meaning some earn much more than others.
CCAvg (1.8): Most people have similar average credit card spending, so their spending habits are pretty close to each other.
Mortgage (0): Everyone in the middle group has the same mortgage situation (most likely none), indicating a lack of variety here
Overall, the data shows a diverse group of people in terms of age, experience, and income, but their credit card spending is similar, and most don't have mortgages. This can help in making better marketing and product decisions.
IQR is useful for identifying outliers as well.
18. The Pearson correlation coefficient between Income and CCAvg (Credit Card Average Spending) is approx. 0.646.
Interpretation:
There is a moderately strong positive correlation between Income and CCAvg (0.65), indicating that higher-income individuals are more likely to spend more on their credit cards.This suggests a tendency for customers with hig
19. Results :
Number of customers using online banking: 2984
Number of customers using online banking: 2016
Conclusion: The data shows that online banking users tend to have higher incomes by an average of approximately 1.33 units compared to offline banking users.
20. Out of all the income values in our dataset, only 2 observations have z-scores beyond ±3 ( higher than compared to the other z_score (mean). This suggests that these 2 observations are significantly different from the rest of the data may need to be examined separately.
Outliers can affect analyses like averages and correlations, so it's important to consider whether these extreme values are errors, anomalies, or significant insights.
