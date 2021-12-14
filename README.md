# Project Name
> Build a multiple linear regression model for the prediction of demand for shared bikes

## Problem Statement
- To understand the factors on which the demand for the shared bikes depends. Specifically, BoomBikes want to understand the factors affecting the demand for these shared bikes in the American market. 
- The company wants to know:
  - Which variables are significant in predicting the demand for shared bikes.
  - How well those variables describe the bike demands

## Conclusions
### The best predictors that business can look upon 

#### For numerical values
- **temp** - with unit increase in temp the cnt increases by .53 times
- **yr** - as yr increases by a unit, the cnt increases by 0.22 times
- **hum** - as humidity increases by a unit, then cnt decreases by 0.16 times
- **windspeed** - as windspeed increases by a unit, then cnt decreases by 0.18 times

#### For Dummy variables
- **winter** - when effects of season is taken into account, winter will increase the cnt by 0.13 times than the reference group (spring)
- **sep** - when effects of months is taken into account, sep will increase the cnt by 0.12 times than the reference group (january)
- **summer** - when effects of season is taken into account, summer will increase the cnt by 0.10 times than the reference group (spring)
- **aug** - when effects of months are is into account, aug will increase the cnt by 0.05 times than the reference group (january)
- **sun** - when effects of weekday are is into account, sun will increase the cnt by 0.05 times than the reference group (monday)
- **workingday** -  the cnt will decrease by 0.04 times when its a workingday
- **oct** - when effects of months is taken into account, oct will increase the cnt by 0.04 times than the reference group (january)
- **holiday** - the cnt will decrease by 0.05 times when its a holiday
- **weathersit(2)** - when effects of weather status is taken into account, cnt will decrease by  0.05 times than the reference group (Clear, Few clouds, Partly cloudy, Partly cloudy) when weather is Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
- **weathersit(3)** - when effects of weather status is taken into account, cnt will decrease by  0.24 times than the reference group (Clear, Few clouds, Partly cloudy, Partly cloudy) when weather is Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds


## Technologies Used
- Python 3.8.8

## Contact
Created by [@Silapada-Hansda] - feel free to contact me!

