# UK Temperature Analysis and Forecasting Project

A data science project analysing temperature changes in the UK over the past 150 years and forecasting temperatures for the next 30 years
## The Problem and Objectives

One of the biggest challenges humans face as a species is the fight against climate change and global warming. With global temperatures increasing at a faster rate than at any point in history, the world we live in and the ecosystems we rely on are struggling to adapt, meaning species around the world are at risk of extinction. Climate data is going to be cruical moving forward as a part of this fight against global warming, helping us to analyse and understand the changes that are happening and predict potential future outcomes. 

The aim of this project is to use UK climate data from the Met Office website in order to analyse how temperatures have changed over the last 150 years, before using Python to forecast how temperatures could change over the next 30 years, related to the previous data.
## Solution Strategy

The solution to the problem will involve the use of a machine learning forecasting model to predict future temperature changes.

Step 1 - Data Collection: This step will involve acquiring UK climate data from the Met Office website, which from prior research is seemingly available in txt format. This data should have temperatures for the UK and it's different regions.

Step 2 - Data Cleaning and Preprocessing: Since the data seems to be in text format there may be some formatting issues to resolve. This section will aim to prepocess the data into a suitable format for analysis before cleaning the data, checking for nulls, duplicates and ensuring all data types are correct too. 

Step 3 - Exploratory Data Analysis: This stage will mainly include analysing trends of temperature changes over the past 150 years in the UK, mainly looking at mean temperature changes and maxiumum temperatures per year and also rainfall, to see if there has been any significant changes in this period, and if so when they were.

Step 4 - Forecasting Model: In this section I will use machine learning to forecast the next 30 years temperatures in the UK. Multiple models will be used with the most accurate one being utilised and the Root Mean Standard Error (RMSE) will be used to measure this.
## Top 3 Data Insights

- UK mean temperature has increased rapdily in the past 30 years compared to the previous 100 years

![Alt text](https://github.com/mattyh1010/UK-Temperature-Analysis-and-Forecasting-Project/blob/main/UK%20mean%20temp%20Moving%20Average.png)

- Difference in mean temperature between 1885 to 1985 and 1985 to 2022, to highlight the above analysis. However this was not reliable enough due to only using 3 single years.

![Alt text](https://github.com/mattyh1010/UK-Temperature-Analysis-and-Forecasting-Project/blob/main/UK%20Regions%20mean%20temp%20change.png)

- Same analysis as above but making the result more reliable by using 5 year averages looking at 1885-1889 to 1985-1989 and 1985-1989 to 2018-2022. Shows the difference in mean temperature change isn't as great, but still significant.

![Alt text](https://github.com/mattyh1010/UK-Temperature-Analysis-and-Forecasting-Project/blob/main/UK%20Regions%20mean%20temp%20chang%205%20years.png)
## 30 year forecasting model

- ARIMA model used to forecast next 30 years of 5 year rolling averages in UK, shows mean temperatures could potential rise to 10.0 degrees celcius by 2050

![Alt text](https://github.com/mattyh1010/UK-Temperature-Analysis-and-Forecasting-Project/blob/main/UK%20mean%20temp%2050%20year%20forecast.png)

- ARIMA model results: Root Mean Standard Error (RMSE) - 0.45
## Conclusions

UK temperatures have increased significantly in the past 30 years compared to the previous 100 years, highlighting the clear affect of global warming in the UK. If this temperature increase carries on at the current rate the 5 year rolling average could reach 10.0 degrees celcius by 2050. This shows how data can be vital in increasing understanding of climate change in the UK and act as a warning for what could happen should we not make any changes to our environment.
