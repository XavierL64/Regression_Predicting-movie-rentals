# Regression_Predicting-movie-rentals

**Description**

The aim of this project is to create a model to help predict the number of days a customer rents a DVD. The project leverages regression and the scikit-learn package. We compare the performance - using Mean Squared Error as proxy - of a linear regression model and Random Forest Regressor model. The linear regression model is optimised to include only the most predictive features, which are selected using a Lasso model. The Random Forest Regressor model is optimised using hyperparameters selected through grid search with cross-validation. 

**Dataset**

the dataset 'rental_info.csv' has the following features:

"rental_date": The date and time the customer rents the DVD.
"return_date": The date and time the customer returns the DVD.
"amount": The amount paid by the customer for renting the DVD.
"amount_2": The square of "amount".
"rental_rate": The rate at which the DVD is rented for.
"rental_rate_2": The square of "rental_rate".
"release_year": The year the movie being rented was released.
"length": Length of the movie being rented, in minuites.
"length_2": The square of "length".
"replacement_cost": The amount it will cost the company to replace the DVD.
"special_features": Any special features, for example trailers/deleted scenes that the DVD also has.
"NC-17", "PG", "PG-13", "R": These columns are dummy variables of the rating of the movie. It takes the value 1 if the move is rated as the column name and 0 otherwise.
