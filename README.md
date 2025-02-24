# UC-Berkeley-AI-certificate-module-11
There are 426880 cars with different models and features. We want to understand what features influence the used car price. the goal is to predict a car's price based on various features such as make, model, mileage, year, condition, location, and other attributes. We will analyze these car values and then give recommendation to a car dealer on what car to buy, and how much they should sell for. We will identify significant predictors, preprocess the data to handle missing values and categorical variables, and develop a predictive model to estimate used car prices.

1. In this analysis, we first conducted a correlation analysis and find out the import features and its values, to reduce the dummy columns from 27737 to 97 columns.
This is a key to reduce the model size so that much less memory is needed.
2. I then use two regression models for the study, linear regression and Random Forest. It is apparently that the random forest prediction is much better.
3. next step, I can dive into the model and carefully choose more related features for the analysis, and also optimize some of the model details, for a better predcition.
