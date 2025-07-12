# Bike Sharing System
## 🧠 Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis, either for a price or for free. Many systems allow users to borrow a bike from a computer-controlled dock after entering payment information, and the bike can then be returned to another dock within the same system.

BoomBikes, a US-based bike-sharing provider, has experienced a significant decline in revenue due to the COVID-19 pandemic. In an effort to recover and grow post-lockdown, the company aims to develop a data-driven business strategy to understand future demand trends.

To support this, BoomBikes has partnered with a consulting company to identify the key factors influencing bike demand. Using historical data on bike rentals, weather conditions, and other variables, the goal is to build a predictive model that:

- Identifies the significant variables affecting shared bike demand.
- Explains how those variables correlate with demand fluctuations.

## 🎯 Business Goal

The objective is to model the daily demand for shared bikes based on independent features. This model will help management:
- Understand how demand varies with key factors.
- Optimize operational strategies to meet projected demand.
- Plan for expansion into new markets based on demand dynamics.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The project aims to assist BoomBikes in understanding the demand dynamics for shared bikes post the Corona pandemic. The primary goal is to identify significant variables influencing bike demand and to predict future demands accurately.
- This need arises from the substantial revenue dips due to reduced mobility during the pandemic. The project seeks to enable strategic business planning for revenue acceleration post-pandemic.
- The dataset comprises daily records of bike rentals, including variables like weather conditions, seasonality, and user type (casual or registered), spanning across 2018 and 2019.

## Conclusions
- The linear regression model indicates a strong ability to predict bike rental demand, with an R-squared score of approximately 0.852 on the test set, suggesting that the chosen features are highly indicative of demand.
- Seasonal and weather-related variables, alongside the year of rental, significantly affect bike rental demand, highlighting the importance of strategic planning around these factors.
- Continuous monitoring and adjustment of the model are recommended as more data becomes available, especially considering potential shifts in user behavior post-pandemic.

## Technologies Used
- pandas - for data manipulation and analysis.
- scikit-learn - for building the linear regression model and performing data preprocessing and model evaluation.
- matplotlib - for data visualization and graphical analysis of model predictions.

## Acknowledgements
- Problem statements and methodlogies derived from Upgrad and IIITB course
- Insights and methodologies were derived from peer analyses and community discussions.
- Utilized Stack Overflow for troubleshooting and optimizing data manipulation techniques.

## Contact
Created by Ravikiran Krishnaprasad - feel free to contact me!

