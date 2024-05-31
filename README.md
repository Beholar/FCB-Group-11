# Fruit Market Analysis
![](https://github.com/Abutujj/FCB-Group-11/blob/main/Cover%20page.png)


## Introduction
The global fruit market is a dynamic and vital component of the agricultural sector, encompassing a wide range of fruits produced and consumed worldwide. It plays a crucial role in the economy by contributing significantly to agricultural output, trade, and employment. This market analysis aims to provide a comprehensive overview of the current state of the fruit market, highlighting key trends, consumer and cost effective choices and other pertinent factors for improving the market.

## Market Overview
The fruit market is characterized by its diversity, with a vast array of fruits consumed/ sold. Major categories includes (Pineapples,Apples, Apricot, Grapes and Peaches).Each category has distinct market dynamics influenced by factors such as market price, forms and consumer preferences.

## Problem Statement
- Inefficient consumption patterns leading to waste and excess expenditure.
- Need for data driven insights to inform cost effective decision.
- Need to evaluate the impact of sustainability practices and regulatory requirements on consumer choices.
- Need to examine consumer buying habits, prefrences and factors influencing fruits consumption.

## Skills/Concept demonstration:
The following power bi features were incorporated

- Dax Function
- Quick Measure
- Filter
- Tooltips
- Navigating button
- Formatting
- Slicer
- Cards

## Dax Funtion:
~~~
Average  price = AVERAGE('Fruit-Prices-2022'[Retail Price]) 

Total Loss = ([Total Revenue]-[Total Sales])

Total Revenue = SUM('Fruit-Prices-2022'[Yield])*SUM('Fruit-Prices-2022'[Fruit Count])

Total Sales = sum('Fruit-Prices-2022'[Retail Price])*COUNT('Fruit-Prices-2022'[Fruit])
~~~
## Visualization:
The Report consist of three pages
- Fruit Profile
- Sales
- Household Consumption
- Duplicate of Sales

## Analysis:
Fruit profile Analysis
![](https://github.com/Abutujj/FCB-Group-11/blob/main/Home%20page.png)

Sales Analysis
![](https://github.com/Abutujj/FCB-Group-11/blob/main/Backpage.png)

HouseHold Consumption
![](https://github.com/Abutujj/FCB-Group-11/blob/main/Household.png)





