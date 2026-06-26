# Personal-Project
Project question:
Did the mean height of 12-year-old girls increase from 1985-2019?

Data Source:
This project uses a global, age-specific height dataset downloaded from NCD-RisC. The data includes yearly mean height estimates by sex and age. Link: https://www.ncdrisc.org/data-downloads-height.html

Method:
Filter the dataset to include only 12-year-old girls. 
Use linregress from scipy.stats to estimate the relationship between year and mean height, including the slope and p-value. 
Run a bootstrap resampling loop 5000 times to estimate a confidence interval for the slope. 
Split the data into an early period and a recent period to compare mean heights as a subgroup check.

Main Finding:
There is an increase in the mean height of 12-year-old girls from 1985-2019.

How to Reproduce:
#Download the dataset from above link.
#Open the notebooks from the repo.
#Run the cells.
#Check the regression output, bootstrap confidence interval, and early-vs-recent mean comparison.
