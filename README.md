# AmesHouse-Real-State


During the Data Science course at allWomen (https://www.allwomen.tech/) part of our practice was to work in teams with real situations and datasets. One of these was the AmesHouse Real State, for the business case the company was interested in having a powerful and accurate method to predict the price of houses located in that city.

For that, we work on cleaning and feature encoding the variables. After that, my team and I use cross-validation to evaluate the accuracy for each model and based on that choose what would be the best model. At first, we started by creating a supervised model with no target variable, as a result, linear regression would be a better choice for that scenario. 

Based on that, we ran the multilinear and polynomial regression, first without scaling and then scaling all the variables, to evaluate if scaling would have an impact on the results. Comparing the metrics results, scaling had no huge impact on it, but comparing the two models (multilinear regression and polynomial regression) we could see that the polynomial regression was slightly better than the multilinear regression.

By the end, my team and I started to question if a classification model would be a better choice. So, we choose the 'Price' as the target variable and use the 'BasedModels' function to find what would be the best classification model. 

The results indicated that the Logistic Regression and the Random Forest would be a better choice.  However, if we compared the accuracy of the classification and the regression models the results were quite the same. Because of that my team and I decided to keep simple and present the first model to AmesHouse Real State.

Here you can find two nootebooks:
 1. The first one contains the cleanning and futured engering;
 2. The second one contains the models;
