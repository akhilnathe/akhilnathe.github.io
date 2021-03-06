---
name: Housing Price Analysis
tools: [Python, Tableau, Docker, FastAPI, Octoparse,WebScraping]
image: https://i.imgur.com/DWNdgbV.jpg
description: This project aims to analyze the house prices in the heilbronn district and city and to come up with a machine learning model to predict the prices
---

# Heilbronn House Price Analysis
In this project study paper, I focused on analysing house and apartment prices in the district of heilbronn following the crisp-dm model. Although we followed the crisp-dm model for the minor tasks, the project could mainly be grouped as two main categories: domain research and data analysis. Because of the absense of  preliminary information about the real estate market and its dynamics in germany and heilbronn, i reviewed literatures both to have more information about the market and to create use cases for the second phase which was data analysis.

After collecting the necessary literature, then the data was scraped from the online listing portals succh as immobilienscout and Immonet. This data was cleaned and then processed for further processing. Exploratory data anaysis was done to get a bigger picture and xgboost machine learning model was used for prediction of housing prices based on different features such as location, number of rooms, the area in square meteres. Feature engineering was also performed to get an estimate of how different features affected the pricing.
<br>
<p align="center"><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSvwv1NU4-T_bVzY4MufDC_n_I0f79433jZM1UIXPSvIs8G3jzzVaQkjgBWmDoXHQ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="100%" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></p>