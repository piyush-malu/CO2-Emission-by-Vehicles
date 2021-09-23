# CO2-Emission-by-Vehicles
Problem Statement

As per the data reported by Society of Indian Automobile Manufacturers (SIAM) A typical passenger vehicle emits about 4.6 metric tons of carbon dioxide per year. This assumes the average gasoline vehicle on the road today has a fuel economy of about 22.0 miles per gallon and drives around 11,500 miles per year. Every gallon of gasoline burned creates about 8,887 grams of CO2.This inturn affect the health of all the passengers and people travelling by the mode of transportation and thus leading to their health issue.So the idea behing choosing this dataset is to predict by analyzing the different models of vehicles applying the algorithm of linear regression which can be used given a data which reduces the CO2 emission .During pandemic the CO2 emission was less citing less vehicles on roads but as the people are getting back on track the emissions are rising.

So, I have collected a data set and applied linear regression on this data. This dataset captures the details of how CO2 emissions by a vehicle can vary with the different features. The dataset has been taken from Canada Government official open data website. This is a compiled version. This contains data over a period of 7 years. There are total 7385 rows and 12 columns. There are few abbreviations that has been used to describe the features.

1.Model 

4WD/4X4 = Four-wheel drive

AWD = All-wheel drive

FFV = Flexible-fuel vehicle

SWB = Short wheelbase

LWB = Long wheelbase

EWB = Extended wheelbase


2.Transmission

A = Automatic

AM = Automated manual

AS = Automatic with select shift

AV = Continuously variable

M = Manual

3 - 10 = Number of gears



3.Fuel type

X = Regular gasoline

Z = Premium gasoline

D = Diesel

E = Ethanol (E85)

N = Natural gas

Make= Company of the vehicle

Model= Car model

Vehicle Class= Class of vehicle depending on their utility, capacity and weight

Engine Size = Size of engine used in Litre

Cylinders= Number of cylinders

Transmission = Transmission type with number of gears

Fuel type =Type of Fuel used

Fuel Consumption City=Fuel consumption in city roads (L/100 km)

Fuel Consumption Hwy=Fuel consumption in Hwy roads (L/100 km)

Fuel Consumption Comb=The combined fuel consumption (55% city, 45% highway) is shown in L/100 km

Fuel Consumption Comb mpg =The combined fuel consumption in both city and highway is shown in mile per gallon(mpg)

# What is done ?
1.First I imported the dataset into colab and analyzed and understood the data set properly by going through some of the info like columns, info, etc.

2.After analyzing, I found the correlation between all colums and plotted the graph to find out relation between different columns using heatmap.

3.Then I spillted the data set into train set and test set. I will use train set to create and train the model and test test to further test and found the accuracy at the end.

4.I applied Linear Regression and fitted the data set and then did the prediction on the test set.

5.I scatter the prediction of Y (student condition) as per the input X_test using matplot library and then plotted using seaborn library.

6.At last I found the accuracy of the prediction.

7.Additionally i have few other things to the dataset like Ridge and Random Forest.

