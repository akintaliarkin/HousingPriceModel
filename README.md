# Project Name
> Build a regression based machine learning model for the prediction of the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
We have a data set from the sale of houses in Australia. We want to build a regression based machine learning model to predict the price of a given house. We also want to:
* Know which variables are significant in predicting the price of a house.
* Know how well those variables describe the price of a house.
* Apply Ridge/Lasso regularization techinques to handle any overfitting in the model.


## Conclusions
Below are the conclusions after building 3 models. One without regularisation and the other 2 models using regilarisation techniques (Ridge & Lasso)
- The model built with out regularisation has clearly overfitted with `r2score (Trainging)` as `0.959` and `r2score (Test)` as `0.756`.
- So the need has arrised to use regularisation techniques to optimally tune the model complexity.
- The optimal value of alpha (hyper-parameter) for the model built using ridge regularisation was found to be around `1`
- The optimal value of alpha (hyper-parameter) for the model built using lasso regularisation was found to be around `100`. We can also see that the lasso technique has eliminated 156 features simplifying the model representation.


## Technologies Used
- Pandas - Version 1.3.4
- matplotlib - Version 3.4.3
- Seaborn - Version 0.11.2
- Numpy
- statsmodel
- sklearn


## Acknowledgements
- This project mainly applies the concepts of Linear/Polynamial Regression, Ridge and Lasso Regression concepts.
- The data dictionary provided by the client was used for understanding the data.
- Resources on the web were consumed to understand various aspects of model building.
- Various documentations were consumed for syntax help.


## Contact
Created by [@akintaliarkin] - feel free to contact me!
