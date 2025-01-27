# Bike Sharing Assignment
A bike sharing system is a set-up of sharing bikes for travel within towns. Bikes are picked from a dockt, and dropped at another dock of the same system. The payment and rental is computerized. Once the information and payment is done the bike is unlocked.
This assingment aims to create a MLR for such a bikesharing system called BoomBike to review the bike demands and impacting variables.

## Table of Contents
* [General Info](#general-information-of-the-requirement)
* [Predictors](#predictors)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information of the requirement
BoomBike is the bike sharing system in US. In pandemic company had dip in their revenue and now it wants to decide on the plan to increase the revenue once lockdown comes to an end.
### The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Predictors
- const                    0.247414
- yr                       0.229130
- holiday                 -0.105315
- temp                     0.567148
- hum                     -0.167113
- windspeed               -0.192660
- mnth_Jan                -0.039188
- mnth_Jul                -0.043961
- mnth_Sep                 0.092930
- season_summer            0.075622
- season_winter            0.125840
- weekday_Tue             -0.045591
- weathersit_Light_Rain   -0.242951
- weathersit_Mist         -0.053978

### Final equation:
##### cnt = 0.2474 + 0.22  * yr - 0.10 *holiday + 0.567148 *temp - 0.167113 *hum 
##### - 0.192660 *windspeed - 0.039188 *mnth_Jan- 0.043961 *mnth_Jul + 0.092930 *mnth_Sep 
##### + 0.075622 *season_summer + 0.125840 *season_winter - 0.045591 *weekday_Tue- 0.242951 *weathersit_Light_Rain 
##### - 0.053978 *weathersit_Mist

## Technologies Used
- Pandas version: 2.2.2
- NumPy version: 1.26.4
- seaborn version: 0.13.2
- statsmodels version 0.14.2
- sklearn version 1.4.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to IIIT-B and Upgrad


## Contact
Created by [@[githubusername](https://github.com/kandiadi)] - feel free to contact me!



