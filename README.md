# Predicting Food Inspection Outcomes in Chicago
**CS109A (Fall 2016) Final Project**<br>
Calvin J Chiew, Angelo Kastroulis, Tim Hagmann<br>
TF: Taylor Names<br>

## Background
In an effort to reduce the public’s exposure to risk of food-borne illnesses, the [City of Chicago](https://github.com/Chicago) has developed a predictive model to [forecast food inspection outcomes](http://chicago.github.io/food-inspections-evaluation/) so that food establishments with high risk of failure can be prioritized for inspections. The new data-optimized approach to food inspections allows errant establishments to be identified earlier. Their project is now open source on [GitHub](https://github.com/Chicago/food-inspections-evaluation), allowing others to implement and refine their model.

## About Our Project
Using the publicly available dataset of about 130,000 food inspections in Chicago since 1 January 2010, we will develop a model for predicting food inspection outcomes. Building on the intuition gained from Chicago’s project, we will examine how variables contained in the dataset, as well as other factors such as day/month/district affect inspection outcomes. We will also explore climate data from the National Centers for Environmental Information, as well as business licenses, crimes and 311 sanitation code complaints data from Chicago’s open data portal. Contrary to the original project, we will be coding in Python instead of R.

## File Layout
Our directory structure is as follows:

DIRECTORY           | DESCRIPTION
--------------------|----------------------
`.`                 | Project files such as README
`./data/`           | Raw data files
`./reports/`        | Reports and other outputs

## Preliminary Modelling
Please see [modeling.ipynb](https://github.com/angelok1/cs109project/blob/master/modeling.ipynb) for our baseline and preliminary models for Milestone #4/5.
