# Accident-Severity-Prediction

The goal is to help predict the severity of an accident based on various conditions. The original Data File came with various columns associated with the time of the accidents on I-95 and US-1 (such as windspeed and precipitation). However, the data was not usable just yet. So, that leads to Part 1: Cleaning the Data.

Part 1 Summary

Part 1 was all about making the data useable, so this part involved the cleaning, transforming and converting of the various columns to the appropriate datatype (such as putting the Start and End time of an accident to a Date-Time format). After cleaning, I did a preliminary analysis of the data.

Part 2 Summary

Before creating the model, I did a preliminary analysis of the data. This involved comparing accident severity and the amount of accidents to various condiditons in the form of various charts. For example, one of the most extensive charts involved comparing accident severity to all of the columns. Here are some general extrapolations from the analysis:

The most amount of accidents happened on I-95 by a wide margin
Accidents more frequently occured in the day in rainy and cloudy conditions
Accidents occured the most in Miami compared to other cities
Accidents occured mostly in the morning hours (7-9) or afternoon hours.(15-18)
Part 3 Summary

After doing a preliminary analysis, I attempted three models: a logistic regression model, a random forest classifier and finally a gradient boosted classifier. I accounted for Multi-colinearity, Heteroskedasticity, and Endogenity and dealt with those issues accordingly. Following, I analyzed the highest rated model using feature importance, Partial Dependance Plots, and Shap values. Finally, I used feature selection to accuratly tune the model to increase the accuracy of the models.
