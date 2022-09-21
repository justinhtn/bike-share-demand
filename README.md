# Bike-share demand modeling using linear regression

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Within this repositiory, I am seeking to model demand for shared bikes based on the available independent variables provided in the dataset entitled day.csv. It will be used by the management to understand how exactly the demands vary with different features. Managment will be able to use this information to manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- A consulting company has contracted with the bike sharing company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

As a recommendation to our business partners looking to predict bike rental demand, we'd recommend leveraging the following features when productionizing a linear model. These are the top 5 predictors of bike ridesharing demand based on our linear regression analysis.

1. <b>light_snow</b>
    If there is light snow, its likely that we'll see a decrease in the demand for bike rentals.
2. <b>yr</b>
    The year in which an individiaul decies to register for a bike share has incredible impact as a predictor of demand. It is our largest predictor with a positive correlation to demand count. As ride sharing company continues to grow, it makes sense that demand would increase as well as popularity and word of mouth increases. 
3. <b>temp</b>
    Temperature is our second largest predictor with a positive crrelation. As the temperature rises, we can see a slow increase in the demand for bike rentals. 
4. <b>spring</b>
    Interestingly enough, during spring there is a slight negative correlation with increase bike rental demand. 
5. <b>winter</b>
    Last but not least, there is slightly higher demand for bike rentals during the winter, but lower demand if its snowing!

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- sklearn
- statsmodels
- pandas
- numpy
- plotly

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@justinhtn] - feel free to contact me!
