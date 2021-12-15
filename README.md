# Boom Bikes
> Bike Sharing Case Study which will help the Boom Bikes to understand what season and environement infuence the Bike sharing Business..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This case study is to apply Machine Learning technique to solve the business problem of Boom Bikes a bike sharing company. Solving this assignment will give an idea about how linear Regression is used in real business problems.

- What is the business probem that your project is trying to solve?
	Boombikes business wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the market

	*	Which variables are significant in predicting the demands for shred bikes.
	*	How well those variables describe the bike demands.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 6 seems to be a good model. We got Adj R-square for training: 0.82 and test: 0.80. This model can generalize and predict demand from new data set
- Top predictor variables:
	- temperature(temp): coefficient of 0.442, indicates a unit increase in temeprature variable will increase the bike hire number by 0.442.
	- year: coefficient of 0.234, indicates a unit increase in year will increase the bike hire number by 0.234.
	- weather Situation(weathersit): coefficient of -0.1932, indicates if the weather situation gets bad by one level then bike hire number goes down by -0.193.
	- windspeed: coefficient of -0.145, indicates if the wind speed increases one unit, the bike hire goes down by -0.145.
	- Season(season_winter): coefficient of 0.105, indicates in winter season the bike hire goes up by 0.105
- Note: weather Situation levels are detailed in the data description file Readme.txt.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
### python libraries
	- pandas, numpy

### for plotting
	- seaborn,matplotlib

### for machine learning
	- sklearn, statsmodels


### for statistical and tests
	- scipy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project was created as part of AI & ML program Sept 2021, Upgrad 
- This project is based on Liner Regression model.


## Contact
Created by [@2bibhu] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
