# Bike-share demand modeling using linear regression

Within this repositiory, I am seeking to model demand for shared bikes based on the available independent variables provided in the dataset entitled day.csv. It will be used by the management to understand how exactly the demands vary with different features. Managment will be able to use this information to manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

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
- statsmodels==0.13.2
- plotly==5.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
