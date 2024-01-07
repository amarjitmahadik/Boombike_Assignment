# Boombike Assignment
> Project Description:
The project involves building a deman prediction model for BoomBikes, a US-based bike-sharing provider. 

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
BoomBikes, a US-based bike-sharing provider, is tackling revenue challenges caused by the COVID-19 pandemic. To prepare for the post-lockdown market, they have enlisted a consulting firm to analyze factors influencing shared bike demand in the American market. The project aims to identify key variables affecting bike demand and create a predictive model to understand how these variables correlate with demand.

Leveraging a comprehensive dataset that includes meteorological surveys and lifestyle factors, the project seeks to provide actionable insights for BoomBikes' management. By modeling bike demand, they intend to adjust their business strategy, meet customer expectations, and position themselves for profit in the evolving market. The project's ultimate goal is to equip BoomBikes with the knowledge needed to navigate post-pandemic challenges and make informed decisions for sustainable growth.

## Conclusions
As we can see the model for predicting the demand is as below

R𝑒𝑛𝑡𝑒𝑑𝐵𝑖𝑘𝑒𝑠=0.493×𝑎𝑡𝑒𝑚𝑝+0.232×𝑦𝑟−0.138×ℎ𝑢𝑚−0.164×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑−0.055×𝑜𝑘𝑤𝑒𝑎𝑡ℎ𝑒𝑟−0.237×𝑏𝑎𝑑𝑤𝑒𝑎𝑡ℎ𝑒𝑟+0.124×𝑆𝑢𝑚𝑚𝑒𝑟+0.0967×𝐹𝑎𝑙𝑙+0.164×𝑊𝑖𝑛𝑡𝑒𝑟−0.0834×ℎ𝑜𝑙𝑖𝑑𝑎𝑦

The top 3 variables for predicting the demand are:
1. Feeling Temperature: Temperature is positively corelated with demand. The higher the temperature, higher the demand. 
2. Bad weather: This variable is neh=gatively corelated with demand. If there is rain or snow the demand is lower. 
3. Year: This variable is positively corelated and hence we see the demand is higher in 2019. We can safely assume that the trend for shared bikes is picking up and is supposed to go higher as we move out of pandemic.

## Technologies Used
The project uses standard python libraries:
- numpy & pandas for data handling
- matplotlib.pyplot & seaborn for data visualization
- model_selection, preprocessing and metrics from sklearn for data preparation and model evaluation
- statsmodels for model building

## Acknowledgements
Give credit here.
- This project was inspired by upgrad

## Contact
Created by [@amarjitmahadik] - feel free to contact me!
