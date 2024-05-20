# Excel-Census-Income-Analysis

### Project Overview

This project looked at loading an Excel file, cleaning the data and then creating charts, visualizations and reports to look at the data of a census income file.

### Data Sources

The main data source used for this analysis is the "CensusIncome-Graduate.xlsx" containing information about data results from a census.

### Tools

- Excel - Data Cleaning
- Excel - Data Visualization / Creating reports

### Data Cleaning

In the inital phase I handled
1. Data loading and inspection
2. Handling missing data
3. Data Cleaning and formatting


### Results/Findings

After the completion of this project, we were able to make some observations on the data.  We are going to discuss various observations that stood out to us when looking at the data and graphs. There are some observations that stood out at first glance, and when looking at the data and connecting the graphs, it made a lot more sense.

Before the data analysis was completed, we first needed to clean the dataset. First we determined the type of variables and then created descriptive statistics for age, education.num and hours.per.week. We then looked at each variable and if more than 50% was missing, we deleted the column. We dropped the capital.gain and capital.loss columns as 92% and 95% of the data points in these columns were “0”, respectively, and this value was meaningless to us and our analysis. We then replaced missing data in the numerical variables by replacing with the average of the variable, and for categorical variables, replaced missing values with “Unknown”.

By briefly looking at the descriptive statistics to get an idea of what kind of data we are looking at, we see that the average age is around 38 and the average hours per week of work is around 40, so the data as a whole represents an average person who has been working for what we would expect to be around 15 years and also working a normal 40-hour week.

When first looking at the income by race graph, it appears that the race that makes more than 50k income a significant amount more than others is White, however if you look at the pie chart showing the count of races in the dataset, 85% of the data points are White. This therefore makes sense that when looking at income by race that there is going to be more Whites making more than 50k compared to other races, because there are simply just more data points from this race.

The sex and income graph at first glance indicates that males tend to make more than 50k a lot more than females. By looking at the occupation by sex and income by occupation graphs and data, it is obvious to see that a lot more males tend to work in occupations that pay more than 50k compared to females. An example of this is the occupation “craft repair”. Out of the 4099 data points of people working in craft repair, 3848 of those are males. Of those 4099 who work in craft repair, 3170 of those are making more than 50k. This is one way we can try to explain why the data shows males tend to make more money than females, however with their simply being so many more data points for males, it does not truly represent what the data should show.

One trend we see is that in every occupation, there is more males than females that are in each occupation and this is due to the fact that 66% of the data points are males, however one outlier than we spotted was that more females work in adm-clerical (2503) compared to males (1227).

In summary of our project, we could draw a few solid conclusions on the data. Even though we could clearly see the single variable statistics through the graphs, we tried and relate them to other graphs to help better our understanding. Missing data is sometimes a factor that can affect results of an investigation, however with this dataset there was not too many missing data points that we had to navigate.

