# diamondPricePrediction
### This repository contains the whole process to build a machine learning model to predict diamond price and also deploy it using Flask web framework.
Today, a diamond ring is an absolute necessity when proposing. But buying engagement ring is the most stressful purchase because there is so much money at stake and so little transparency. 
To solve this problem, I build a model using xgboost to predict the diamond price.
In order to build this model. First, I collect the diamonds data including the price and 11 different features by using web scraping. And then I trained this machine learning model using 90% of the data and then test it again using the rest 10% of the data. MAPE for this model on test set is 5.25%.
To deploy this powerful machine learning model I built, I created an interactive website. In this website, with all the different diamond features entered, it would give you a market price of this diamond. With this predicted fair market price, the customer can determine if they are overpaying or underpaying.
