# University of Illinois MS Weather and Climate Risk and Data Analytics Capstone Project
## ATMS 596

This is the capstone of Michael Reis for the University of Illinois MS Weather and Climate Risk and Data Analytics Capstone Project.

The project's aim is to analyze the relationship between weather and climate-related disasters's geographical location, deaths, people affected, damage, and the hazard itself.  The disaster data is taken from EM-DAT for years 1900 to Dec 1, 2025 (pulled on Dec 7, 2025), but only data 2000 and beyond are used for the purposes of deep analysis due to data concerns.

The first part of this project creates a function which can interpolate the amount of damage that a disaster has by using other variables: country, GDP per capita, deaths, and number of people affected.  This is useful to fill in gaps that the the EM-DAT data misses due to lack of information.

The second part of this project connects the data in the disaster database to weather and climate data -- the IBTrACS data for tropical cyclones.  This data was pulled on December 7, 2025 with data updated last on December 4, 2025.  By looking at the max intensity of a storm over a country, we can much disaster related data, like people affected, deaths, and damages, are correlated with the storm severity.