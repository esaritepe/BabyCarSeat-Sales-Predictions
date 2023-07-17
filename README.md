# Best Predictive Model for Baby Car Seat Sales

<p align="center">
  <img src="https://data.family-nation.com/imgprodotto/safety-1st-sweet-safe-baby-car-seat-group-0-1-full-red-0-18-kg-car-seats-group-1-2-3_47602.jpg" width=200/>
</p>

Project Goal 
-----------
* Determine which regression model (stepwise selection, best subset selection, and decision trees) would best predict baby car seat sales based on store location characteristics. 

File Structure
---------------
* A Rmd file that contains the R code that models baby car seat sales using stepwise selection, best subset selection, and decision trees. Statistical analyses were also performed on the file to determine which regression model has the best reliability.
* A CSV file is also included, featuring data on the store location's Price, Competitor Price, Income, Education, Age, Advertising, Accidents, Urban, US, Sales, and Shelving Location.
  
Contribution 
-------------
* This was a group project done with Jin Chen, Beom Ki Lee, and Sushant Varghese

* __Results:__ A 5-predictor multilinear regression model using either stepwise or best subset selection was more reliable than the decision tree model, with a 12% reduced RMSE and 2% improved correlation. 
* Suggested a new linear regression model that would predict baby car seat sales based on the location characteristics of price, education, age, advertising, and shelving location. 
