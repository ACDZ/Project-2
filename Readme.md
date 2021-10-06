# Problem Statement
We are a data team of a AIMS, a real estate investment company specifically looking at property based in the middle of the United States.
The management saw that the returns in Ames, Iowa have been dismal and would like the data team to see if we can help the purchasing team and sales team in Ames.
After speaking to both the sales and purchasing teams we have come to the conclusion that the purchase teams likes to only buy expensive and new property. There is a human bias chasing after the new and the shiny. Leaving much of the used homes behind.

We would like to see if we can create a model that can predict property prices quite accurately.
Our model can predict the sale price of properties based on the features of a property unit, and by doing that we can identify properties that are currently sold below market price and add these into our portfolio for a good return on investment.

# Summary

Three models were tested for the prediction, namely, Linear Regression, Lasso Regression and Ridge Regression.
The Null Model had a RMSE of 78038.
The predictive models had to beat that score by have a error score below that.

The model chosen for prediction was the lasso regression model from sklearn.
The model had R^2 0.929 for its train test and R^2 0.927 for its test data.

It's RSME score was 20936 for train data and 21109 for test data.

All in all, the lasso model had an accuracy of 92% and performed better than the mean of sale prices.

# EDA
There were 81 variables in the Ames Dataset and the important variables were compared in a histogram to check for patterns we can infer.
The important variables were the following:

#### General Living Area Above Ground
The space of the building above the ground, including 2nd floors.
This is the most critical variable with regard to price of property.
The variable, the higher the price.

#### Overall Qual
The overall quality of the property was the next strongest factor in determine sale price.

#### Other important variables:
Total basement squarefeet, age and the neighborhood of Northridge Heights and Stonebrook.

# Data Dictionary
A very good data dictionary can be found here:
http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

# conclusion

<img src="../images/actual_vs_predicted.png" style="width:600px; height:400px"/>

The model predicted well. However, I believe that the model can be further improved if there was more recent data.

### Going forward

1. We wish to help the purchase team even more by coming up with automated scoring system, to help them make decisions quickly.
2. We also want to input new features, like psf, rental prices, size of backyard, color of the walls, roof, whether the previous owner had pets etc.
3. We may also take out features we deem do not affect the model.
4. We aim to refresh the model every quarter especially just before the summer months to provide the most accurate data for prediction.
5. We would also like to test the model on other cities with similiar data and variable availability.
6. We would like to find data from 2011 onwards to see if the trends have changed over the years.
"# Project-2" 
"# Project-2" 
"# Project-2" 
