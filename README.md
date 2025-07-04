# DSA-Amazon-project




## Table of Content

- [Project Overview](#Project-Overview)
- [Data source](#Data-source)
- [Problem Statement](#Problem-Statement)
- [Tools used](#Tools-used)
- [Skills demonstrated](#Skills-demonstrated)
- [Data Analysis](#Data-Analysis)
- [Visualisations](#Visualisations)
- [Insights from analysis](#Insights-from-analysis)
- [Conclusion and Recommendations](#Conclusion-and-Recommendations)
  
## Project Overview
This project explores the profiles of the world’s richest individuals using a structured dataset. It includes insights into net worth by industry, country, and self-made status.
In addition, it maps macroeconomic metrics like GDP and tax rates to billionaire distribution. Visualisations are created using Excel for intuitive storytelling. The project highlights trends in wealth, economic context, and demographic influence.


## Data source
Key columns in the dataset include rank, category, name details, demographics, net worth (in millions USD), company location and economic metrics by country like

- cpi_country – Consumer Price Index
- gdp_country – GDP
- life_expectancy_country
- tax_revenue_country_country
- total_tax_rate_country
- population_country

This dataset was downloaded as a .csv file from a google drive link.
  
## Problem Statement
Despite rising global inequality, little is understood about how personal wealth among the ultra-rich aligns with broader economic conditions. This project seeks to uncover patterns in billionaire wealth by industry, geography, self-made status, and national economic indicators, helping us understand the socio-economic context behind wealth accumulation.

## Tools used
Excel

## Skills demonstrated
1. Data cleaning, preparation and transformation

- Standardized Gender Values
Using Find & Replace via the Home tab > Editing > Find & Select > Replace, the values in the gender column were standardized by replacing "M" with "Male" and "F" with "Female".
- Calculated Date of Birth
A new column titled Date of Birth was created using the formula:
=DATE(birthYear, birthMonth, birthDay)
The autofill handle was used to apply this formula to the entire column.
- Inserted Current Date Column
A new column titled Current Date was inserted before the Date of Birth column. The formula =TODAY() was used to populate it and autofill was applied to the remaining rows.
- Calculated Age
Using Excel’s YEARFRAC() function, a new column was created to calculate the age:
=YEARFRAC(Date of Birth, Current Date)
This value was autofilled for all entries.
- Cleaned GDP Values
In the gdp_country column, commas were removed for numerical consistency using Ctrl + H - replacing all, with an empty string.
- Reordered Columns
The Age column was moved to appear after the population_country column using drag-and-drop with the Shift key held.
2. Data analysis
  
3. Data visualization
   
4. Dashboard development

5. Data structuring

6. Insight generation

## Data Analysis

- Descriptive Statistics:
Descriptive statistics were performed using Excel’s Data Analysis Toolpak. The Analysis Toolpak add-in was enabled, and the dataset was analyzed by selecting “Descriptive Statistics” and checking the box for "Labels in First Row".

![Descriptive_statistics](Descriptive_statistics.xlsx)

- The following Pivot tables and charts were created:
  1. Gender vs Count of Gender
  2. Category vs Sum of Final Worth (Top 10 Categories)
  3. Country vs Count of Last Name (Top 5 Countries)
  4. Age vs Count of Age
  5. Category vs Tax Revenue (Top 5 Categories)
  6. Category vs Tax Revenue (Bottom 5 Categories)
  7. SelfMade vs Count of SelfMade
  8. Country vs Sum of GDP

## Visualisations
A comprehensive dashboard was developed by assembling the pivot charts to allow for interactive insight into wealth, industries, and demographics.

Slicer Application:
Slicers were added via Insert > Slicer, allowing dynamic filtering by fields such as gender, country, category, and selfMade.

![Billionaire_dashboard](Billionaire_dashboard.PNG)


## Insights from analysis

1. Gender Disparity
There is a significant gender gap: **407 males vs. 68 females** (over 85% are male). This reflects a persistent imbalance in global billionaire demographics.

2. Wealth Concentration by Industry
Technology leads in total final worth, followed by Fashion & Retail and Finance. High returns and scale in tech likely drive billionaire accumulation.

3. Country Concentration
The United States has the highest number of billionaires and dominates GDP contribution which is followed by *China*, *Germany* and *India*. This suggests global economic hubs.

4. Age Distribution
Most billionaires are in the **60–70** and **80–90** age brackets. This indicates that wealth accumulation is often a long-term process, building over decades.

5. Self-Made vs Inherited Wealth
65% of billionaires are self-made while 35% inherited their wealth. Entrepreneurship and business innovation are dominant wealth paths.

## Conclusion and Recommendations

In conclusion, from this dataset, it was shown that Billionaires are **predominantly male**, **older**, and **self-made**, often in **technology** or **finance**. The **U.S. economy** is a major driver of both GDP and billionaire formation.

Recommendations include:
- Promote Inclusive Wealth Creation
   * Encourage gender parity in business, entrepreneurship, and investment opportunities. Women should be supported in leadership and innovation roles.
- Nurture Young Entrepreneurs
   * Provide incubation, funding, and mentorship for younger talent to bridge the age gap in wealth creation.
- Diversify Economic Growth
   * Invest in sectors with **low billionaire representation** but high potential (e.g., Healthcare, Renewable Energy).
- Support Innovation Ecosystems
   * Focus on digital infrastructure, research and development so as to emulate the tech sector’s success in other industries.



### Back to top 
###### [Table of Content](#Table-of-Content)
