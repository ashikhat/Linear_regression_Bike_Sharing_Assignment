# Linear Regression Bike sharing Assignment
> This is a practice assignment of the linear regression on sharing bikes platform demand.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
In this project the data from US bike sharing provider 'BoomBikes' is Used. The boom bikes want to use the previous data to predict what is affecting the demand of the bikes so that they can prepare a better business model and generate the max revenue

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The equation for the Multilinear regression model is as below, 
Y_pred=0.2306+0.2476xYear+0.0622xweekday-0.1366xwindspeed-0.0835WS2-0.3065xWS3+0.2664xsummer+0.3369xfall+0.2604xwinter
looking at the equation above top three features affecting the bike demand is as below
1.	Fall season (+ve impact on demand)
2.	Weathersituation3 i.e. Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds (-ve impact on demand)
3.	Summer season (+ve impact on demand)


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- seaborn
- scikit learn
- statsmodels
- matplotlib
- python 3.x

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@ashikhat] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
