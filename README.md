# Rossmann-Store-Sales-Prediction-Problem

Forecast sales using store, promotion, and competitor data

Rossmann operates over 3,000 drug stores in 7 European countries. Currently, 
Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

In their first Kaggle competition, Rossmann is challenging you to predict 6 weeks of daily sales for 1,115 stores located across Germany. Reliable sales forecasts enable store managers to create effective staff schedules that increase productivity and motivation. By helping Rossmann create a robust prediction model, you will help store managers stay focused on what’s most important to them: their customers and their teams! 
https://www.kaggle.com/c/rossmann-store-sales

This is a pretty interesting problem cause I always wonder waht can be the relatively vital effects to a store daily sales? My first tuitive on this I think might be weekends to be #1 and then possibily distance to competitors and then promotions (as far as I'm considered I was always "couraged" to buy those "buy one, get one" stuff), well, things would never be that easy.. So here we go, let's focus on the data and example to have an overall view on this prediction problem.

  I'll basically cover the following procedures and those are kinda my thought process.
  
1. Feature Engineering and EDA
   +1.1 Data Preparation
   +1.2 Customers Vs. Sales
   +1.3 Open, StateHoliday Vs. Sales
   +1.4 DayOfWeek Vs. Sales
   +1.5 Date Vs. Sales
   +1.6 Competition Vs. Sales
   +1.7 Promotion Vs. Sales
2. Modeling and Prediction
   +2.1 Rpart Regression Tree and Conditional Inference Tree
   +2.2 Linear Model
   +2.3 Prediction
