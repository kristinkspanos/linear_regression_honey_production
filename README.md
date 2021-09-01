# linear_regression_honey_production
Codecademy project using linear regression to predict future honey production.

In recent years, there has been widespread concern about the decline of the honeybee population in the United States. This project aims to predict the size of the honeybee population into future, based the change in the size of the population between 1998 and 2012. The project uses a linear regression model to create a line of best fit that describes the trend in honeybee production. The line of best fit is then extended to the year 2030, in order to identify the predicted level of honey production if the identified trend continues. 

## built with
* Python 3
* Jupyter Notebook

## data sources
'Honey Production in the USA (1998-2012)' dataset, downloaded from Kaggle.
https://www.kaggle.com/jessicali9530/honey-production

Field | Description
------------ | -------------
state | State name abbreviation
numcol | Number of honey producing colonies
yieldpercol | Yield per colony (lbs)
totalprod | Total production (numcol * yieldpercol), (lbs)
stocks | Stocks held by producers on Dec 15 (lbs)
priceperlb | Average price per pound ($)
prodvalue | Value of production (totalprod * prodvalue), ($)
year | Year the data pertains to

## acknowledgements
* [Kaggle, Jessica Li](https://www.kaggle.com/jessicali9530/honey-production)
* [Codecademy Data Scientist Skill Path](https://www.codecademy.com/learn)
