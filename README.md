# Aviation Risk Analysis Project

## Introduction

In the US court systems, the average compensation for a life lost in a general aviation accident is $5.2 million dollars, the highest in the world!1
This project presents analysis of past aviation accidents based on how the aircraft was built. Our team reviews and processes the data to generate insights for Jelly Co. and ultimately provides airplane purchasing reccomendations.

1([Article](https://www.keystonelaw.com/keynotes/how-is-compensation-calculated-after-an-aviation-accident)) written by Healy-Pratt and Hanna in 2021 

![image](https://storage.googleapis.com/mcp_acc_236blog/uploads/2014/11/018067-vroeg-II1.jpg)

Photo by ([Andres Bolkenbaas](https://blog.klm.com/6-tips-for-creative-aviation-photography/))

## Business Problem
Jelly Co. is expanding it's business to new industries. They asked our team to look into the data for airplane accidents1 within the US in the last twenty-odd years. 
The company wants to know:

```
  1.Which airplane feature helps assess the lowest possible risk to the company?
  2.Which airplane manufacturer should be purchased and operated for a commercial enterprise?
  3.Which airplane manufacturer should be purchased and operated for a private enterprise?
```
Here we are using the ([definition](https://www.faa.gov/faq/what-constitutes-post-accident-test-what-definition-accident#:~:text=The%20FAA%20and%20the%20National,any%20person%20suffers%20death%20or)) of accident: "an occurrence associated with the operation of an aircraft which takes place between the time any person boards the aircraft with the intention of flight and all such persons have disembarked, AND in which any person suffers death or serious injury or in which the aircraft receives substantial damage"

## Data and Resource Used
For this project a ([dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)) was taken from the National Transportation Safety Board that includes:

```
  1.Aviation accident data from 1962 to 2023
  2.Civil aviation accidents
  3.Selected incidents in the United States and international waters
```
In this project:
     * Pyhton 3 is used to clean up data, to impute , to make analysis and visualization.
     * Tableau is used to make our dashboard.
## Methods
The method applied to solve our bussines problem is just by following data science procedures. And the first step is data cleaning.
Data cleaning include:
      * Removing duplicates in this dataset there was 1390 records duplicate.
      * Dropping some columns which are not relevant to our business problems.
      * Some imputation technique is also used.
After cleaning the data. The master dataset was created. And used to make analysis using Python and Tableau.
## Data Analysis Result
Our analysis shows that:
      * Aircraft engine number is correlated to total accident record
      * Aircraft with asingle engine has the highest accident
      * Aircraft with recprocating type of engine has the highest accident.
      * The most accidents occurred during the landing phase of flight.
      
## Airplanes with a minimum of 2 engines had the least amount of accidents
![image](https://github.com/ermiyas-sidama/Aircraft_Risk_Analysis/assets/160514617/91382f04-d84f-4420-8195-d6b4aaf62c0e)

## Airplanes with the recprocating type of engine had the most amount of accidents

![image](https://github.com/ermiyas-sidama/Aircraft_Risk_Analysis/assets/160514617/5979a273-132d-4325-9fce-495778200963)

## The most accidents occurred during the landing phase of flight
![image](https://github.com/ermiyas-sidama/Aircraft_Risk_Analysis/assets/160514617/90768e02-b564-459f-94de-6f1004228c62)


## Reccomendations
### For Commercial Airplanes
```
  1. Make: Airbus
  2. Number of Engines: 4.0
```
### For Private Airplanes
```
  1. Make: Make: Gulfstream Aerospace
  2. Number of Engines: 2.0
```




















