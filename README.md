# Descriptive Analysis

**Initial Year of Project :** 2024

# Project Summary

**Project Title:** Descriptive Analysis of the Norwegian Labour Market, Earnings & Education

**Project Description:**  This project entails conducting a descriptive analysis of the Norwegian labour market, earnings, and education using data obtained from Statistics Norway (SSB). The analysis spans from the year 1972 to 2023 and aims to provide insights into various aspects of the labour market landscape, including unemployment rates, regional disparities, educational trends, vacancies, and earnings across different industries. The analysis utilizes Power BI for visualization to present trends and patterns effectively.

**Problem Description**
**Objective:** Undertanding the current situation of the labour market in Norway. 

**Project Goals**

Analyze trends in the Norwegian labour market from 1972 to 2023.

Explore unemployment rates and reasons over the specified period.

Investigate regional variations in unemployment rates for 2022 and 2023.

Examine educational trends across different fields.

Analyze vacancies and earnings based on various industries for 2022 and 2023.

## Data Analysis Summary
**Data Source:** SSB.no

**Data Cleaning:** 
1.Removing unnesscary text while downloaing data.

2.Choosing specific variables needed for the analysis from SSB

3.Unpivoting required columns in different datasets

## Visualization

<img width="778" alt="image" src="https://github.com/nikhiljohnabe/Norwegian-Labour-Market-Earnings-Education-Dashboard-Analysis/assets/69458001/a090d543-5aa1-4987-a4d7-4680261492e2">

<img width="750" alt="image" src="https://github.com/nikhiljohnabe/Norwegian-Labour-Market-Earnings-Education-Dashboard-Analysis/assets/69458001/464d3383-3850-46eb-a66b-198a949d0c49">


**Analysis Summary:** 

Analysis Summary:

1.We see unemployment rate surges every 8 to 13 years in Norway due to different factors. Once it is compared to other factors such as changes in interest rates, inflation, and other economic factors, we can see that it is highly correlated.

2.Unemployment rates are high in regions such as Oslo and Viken as they are economic hubs and have higher populations than other regions.

3.The unemployment rate is higher among the 25 to 54 age group, which could also imply that there are better policies for hiring younger talent and that education is more relevant to a growing economy like Norway's.

4.It is seen that the highest enrollment is in Health, Welfare, and Sport. This could directly be related to demand in such roles, as seen in the vacancies graph, as Human Health and Social Services have the highest vacant roles within different industries.

5.Although there is high demand in Human Health and Social Services, the profiles are among the least paid among other industries, while mining, quarrying, finance, and insurance are the most paid.

Please Note:

1."Diff%" and "%Diff" are the same. They calculate the percentage change from previous years and are calculated on absolute numbers. Meanwhile, the percentage depicted in tables and charts is the percentage of the grand total of the column. For example, Unemployment by Region has 46.1% in 2022 in Oslo and Viken region, which is the percentage of people unemployed compared to the total across all regions. "Diff%" is calculated as (177-171)/171 = 3.5 percent. [171 - total unemployed in thousands in 2022, 177 - total unemployed in thousands in 2023]

2.The Education stats for 2023 are currently unavailable in the SSB dataset.

## Hardware and Software Used

**Software:** Power BI and Excel 


## Future Steps

1.Explore additional economic variables and factors influencing the labour market, earnings, and education.

2.Conducting deeper analysis on specific segments of the labour market or education sector.

3.Incorporate more recent data to track ongoing trends and developments.

4.Integrating external datasets for comprehensive analysis and insights.


## Conclusion
This section summarizes the key findings and insights obtained from the descriptive analysis of the Norwegian labour market, earnings, and education. It highlights the importance of understanding these dynamics for informed decision-making and policy formulation.

## How You Can View My Power BI Dashboards
For those interested in actually playing around with the dashboard, here are some detailed steps to help you do so:

**1. Download PowerBI**

Go to this site: https://powerbi.microsoft.com/en-us/desktop/ and click the "Download Free" button in the center of the screen (this may change in the future!). There may be a prompt that asks you to download from the Microsoft Store instead, in which case simply click the button that opens the Microsoft Store and install the application from there.

Note: You DO NOT have to sign-in to use this 'Desktop' version, although if you choose to then you'll need to use a work/school email adddress.

**2. Configure Some Settings**

Open Power BI Desktop and simply close the large dialog window that starts. Then, go: File -> Options and settings -> Options. On the left side you'll see two general categories of options: GLOBAL and CURRENT FILE.

Under the GLOBAL options, go to 'Preview features' and de-select all options.

Under the CURRENT FILE options, go to 'Data load' and de-select the two options: (i) Update or delete relationships when refreshing data, and (ii) Autodetect new relationships after data is loaded.

Finally, again under the CURRENT FILE options, go to 'Regional Settings' and make the appropriate selection for your region.

**3. Download My Project Files**

Now that everything is set up, you simply have to download all my project files as they are into a folder on your machine, open the Power BI file (the one with .pbix extension) and have fun!


