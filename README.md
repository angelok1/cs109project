# Predicting Food Inspection Outcomes in Chicago
**CS109A Final Project**<br>
**Predicting Food Inspection Outcomes in Chicago**<br>
Calvin J Chiew, Angelo Kastroulis, Tim Hagmann<br>

## Original Analysis and Reports
In an effort to reduce the public’s exposure to foodborne illness the [City of Chicago](https://github.com/Chicago) partnered with Allstate’s Quantitative Research & Analytics department to develop built an algorithm to [predict likely health code violations](http://chicago.github.io/food-inspections-evaluation/) for restaurants based on publicly available data. They turned this into an open source project, freely available on [github](https://github.com/Chicago/food-inspections-evaluation), so others could implement this model.

## Project Scope
During this project we are going to have a closer look at the model descripted above and we are trying to improve/extent it. Contrary to the original project the coding is principaly done in Python instead of R. Our goal is to accuratly predict restaurants in Chicago that fail an health inspection.

## File Layout

The following directory structure is used:

DIRECTORY           | DESCRIPTION
--------------------|----------------------
`.`                 | Project files such as README
`./data/`           | Data files
`./reports/`        | Reports and other output are located in

## Data Sources
To build a predictive model, we are principaly examining data from five sources.

- Food inspection outcomes since 2010.
- Weather data
- Business licence data
- 311 sanitation complaints
- Crime data in chicago

## Data Exploration
See the following 3 ipython notebooks on GitHub for our preliminary data exploration:
GitHub URL: https://github.com/angelok1/cs109project 
Food inspections dataset: Food_Inspections.ipynb
Business licenses, crimes and sanitation code complaints datasets: business-crime-sanitation.ipynb
Climate dataset: Climate.ipynb

## Current Summary of Findings
Inspection type, past failure and risk category changes the probability of failing a food inspection. Failure rates also tend to increase in the mid-year months corresponding to summer and early fall when temperature is higher. There is also variation in the distribution of crimes and sanitation code complaints by location/district which may be correlated with failed outcome.

