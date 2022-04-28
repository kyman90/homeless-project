# Homelessness and Shelter Beds

## Tableau Dashboard Link
https://public.tableau.com/app/profile/kyle.m.1065/viz/HomelessPresentation/Dashboard5

## Table of Contents
* [Tableau Dashboard](#tableau-dashboard-link)
* [Summary](#summary)
* [Question](#data-question)
* [Data Sources](#data-sources)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)

## Summary
The homeless population in the United States was declared a state of emergency prior to the COVID-19 pandemic. The pandemic only increased the need to provide homeless populations with adequate shelter and services to ensure their health and well-being during a national health crisis. This analysis seeks to examine the homeless populations by categories (veterans, children, and families) along with the number of homeless shelter beds available for these specific populations in each state. With this information, public leaders and non-profit organizations will have a roadmap to indicate which states are the best location to open homeless shelters or increase shelter beds to serve specific homeless population categories.

In my previous profession as a Law Enforcement Officer, I worked very closely with the homeless communities in the City of Los Angeles. I responded to hundreds of calls for service where members of the homeless community required medical assistance, victim assistance, food, shelter, and any other resources. I personally witnessed the vulnerabilities of this community, and I have long hoped to provide additional assistance in an insightful and meaningful manner.

## Question
This project will analyze the homeless population compared to available homeless shelter beds in each state. Furthermore, I will examine the homeless population by categories (veterans, children, and families) and the available number of shelter beds for each of these categories. This project is intended to identify locations/states where the needs for non-profit shelters and shelter beds are the greatest for specific homeless populations. To contribute to the homeless community, I hope that my findings and analytics provide a roadmap to future non-profit shelters and help them identify specific locations where they can best serve specific homeless populations.

## Data Sources
1)	U.S. Department of Housing and Urban Development (HUD)
https://www.huduser.gov/portal/datasets/ahar/2021-ahar-part-1-pit-estimates-of-homelessness-in-the-us.html

2)	U.S Census Bureau
https://www.census.gov/data/developers/data-sets.html

3)	HUD Exchange
https://www.hudexchange.info/programs/coc/gis-tools/?&filter_tooltype=&filter_year=&filter_state=&current_page=2

## Problems and Hurdles
To fully analyze homeless populations, I needed to retrieve government census data through an API to effectively examine homelessness per capita. This information will assisted in evaluating the needs for more homeless beds for certain populations.

Homeless reporting standards changed in 2021 to no longer provide an overall homeless population estimation or an estimation of unsheltered homeless individuals. As a result, only data through 2020 will be utilized for analysis to properly evaluate overall homeless while including both sheltered and unsheltered homeless counts. This data will better demonstrate the need for beds due to analyzing the number of unsheltered homeless throughout the United States.

The government data from the U.S. Department of Housing and Urban Development changed on a yearly basis. The way that homeless populations were reported changed in category types and population types creating inconsistencies and no valid pattern in which required extensive cleaning to normalize. Additionally, specific populations were not directly counted until recent years, and dedicated beds for youth and veteran populations were not allocated until 2017.

## Technologies Used
-Python-
The primary method of analysis in this project was conducted in Python 3, specifically within a Jupyter Notebook.

-Excel-
In order to normalize the data prior to analysis, Excel was used for the purpose of cleaning.

-Tableau-
Upon completion of normalization and analysis, Tableau was utilized to create visualizations and an interactive dashboard (see dashboard link for further).
