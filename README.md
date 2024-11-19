# Bike Rental Demand Prediction
> This project aims to build a predictive model for bike rental demand based on historical data, using various factors like weather, season, and holiday status. The objective is to assist the bike rental company in making informed decisions about inventory management and resource allocation.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
The bike rental demand prediction project focuses on analyzing factors that influence bike rental demand. Accurate prediction of bike rentals is crucial for managing inventory and maximizing user satisfaction by ensuring availability. This project uses a dataset of bike rental records that includes various attributes like weather, season, time, and user types.

- **Background**: Many urban areas have adopted bike-sharing systems as a solution for congestion and pollution. However, fluctuating demand can lead to overstocked or understocked bike stations, affecting customer experience.
- **Business Problem**: The project aims to solve the business problem of optimizing bike inventory by predicting daily rental demand based on factors like weather, season, and holiday status.
- **Dataset**: The dataset used includes bike rental records with features such as casual, registered, season, temperature, humidity, windspeed, workingday, and holiday.

## Conclusions
Features which positively derive the bike rental
- year
- workingday
- temperature
- winter
- Saturday

Features which negatively derive the bike rental
- humidity
- windspeed
- light_snow

Top 3 predictors of bike rental ( in order of absolute value of coefficients )
- Temperature
- humidity
- year


## Technologies Used
- numpy: 1.26.4
- seaborn: 0.13.2
- statsmodels.api: 0.14.2
- sklearn: 1.4.2
- pandas: 2.2.2

## Acknowledgements
This project is inspired by a US bike-sharing provider BoomBikes.

## Contact
Created by [Gunjan-lab-test@githubusername] - feel free to contact me!


