# NBA Analytics : An Exploratory Data Analysis on the NBA data

## Table of Contents
* [Project Overview](#project-overview)
* [Resources Used](#resources-used)
* [Findings](#findings)
  * [Relationship between NBA Player's Weight and Height](#relationship-between-nba-player's-weight-and-height)
  * [Weight and Height Overtime](#weight-and-height-overtime)
  * [Does Weight and Height Affect Player Performance](#does-weight-and-height-affect-player-performance)
  * [Visualizing NBA Players Across Different Countries](#visualizing-nba-players-across-different-countries)
  * [Average NBA Player's Age Throughout the Years](#average-nba-player's-age-throughout-the-years)

## Project Overview
I have always loved the game of basketball and has been a fan of it ever since I was young. I wanted to explore more on this domain and look for interesting findings. Thus, I have decided to work on this project.

In this project, there are a few things that were looked into :
  * Weight and Height Analysis
  * Visualizing NBA Players Across Different Countries
  * Average NBA Players Age

## Resources Used
**Python Version:** 3.8.5

**Packages:** pandas, matplotlib, numpy, seaborn, plotly

**Dataset:** Retrieved from https://www.kaggle.com/justinas/nba-players-data


## Findings
### Relationship between NBA Player's Weight and Height
![image](https://user-images.githubusercontent.com/57311200/119349103-54642200-bcd0-11eb-8a79-db9875a61cad.png)

From the Scatterplot above, notice that as weight increases so does height. Vice versa, as height increases, so does weight

Since we already know from the graph above, there's a positive relationship between nba player's weight and player height. Correlation was calculated to find out how strong the relationship is between these two variables

**The finding of the correlation score is** : 0.83

The correlation score of **0.83** suggests that there is a strong positive relationship between nba player's height and player weight

---
### Weight and Height Overtime
![image](https://user-images.githubusercontent.com/57311200/119349035-38608080-bcd0-11eb-92e5-f191946c4483.png)

The mean for player height and player weight was calculated for each season and plotted using line charts

The line charts shows that the average player height and player weight has been declining from 1996 to 2020

---
### Does Weight and Height Affect Player Performance )
![image](https://user-images.githubusercontent.com/57311200/119350109-83c75e80-bcd1-11eb-8f4c-e4604f26bfe3.png)

Next, a correlation matrix was conducted to find out whether a player's weight and height affects their performance

The targeted variables were : pts, reb, ast, net_rating

From the correlation matrix above we notice that :
 * **Rebound**
   * **Player Height** -> **Correlation** : 0.42
   * **Player Weight** -> **Correlation** : 0.44
 * **Assist**
   * **Player Height** -> **Correlation** : -0.46
   * **Player Weight** -> **Correlation** : -0.40
   
The findings above suggests that **rebound** has a positive moderate relationship with both player height and weight WHILE **assist** has a negative moderate relationship with both player height and weight

Scatterplots below were also graphed to visually see how the variables interact with each other
![image](https://user-images.githubusercontent.com/57311200/119352338-2254bf00-bcd4-11eb-95d1-136735bb3b71.png)

---
### Visualizing NBA Players Across Different Countries
![image](https://user-images.githubusercontent.com/57311200/119353022-f554dc00-bcd4-11eb-88b0-6e1ed480a807.png)
![image](https://user-images.githubusercontent.com/57311200/119352909-d22a2c80-bcd4-11eb-9e69-8381cc70cc96.png)
![image](https://user-images.githubusercontent.com/57311200/119352950-dc4c2b00-bcd4-11eb-8c83-f6b8cb2957d9.png)

---
### Average NBA Player's Age Throughout the Years
![image](https://user-images.githubusercontent.com/57311200/119353270-449b0c80-bcd5-11eb-8504-2b446f2b5113.png)

From the line chart above, it is obvious that the average nba player's age has dropped from 1996 to 2020
