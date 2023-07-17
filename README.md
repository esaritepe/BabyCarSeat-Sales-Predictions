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

Results
-------
<p align="center">
  <img src="https://github.com/esaritepe/BabyCarSeat-Sales-Predictions/blob/main/screenshots/bcs_assumptions.png"/>
</p>
* Checking the regression assumptions for the candidate models using traditional methods

<p align="center">
  <img src="https://github.com/esaritepe/BabyCarSeat-Sales-Predictions/blob/main/screenshots/bcs_best_subset.png"/>
</p>
* Best Subset Selection plots using Mallow's Cp, Adjusted R-squared, and Bayesian Information Criterion (BIC) as performance indicators

<p align="center">
  <img src="https://github.com/esaritepe/BabyCarSeat-Sales-Predictions/blob/main/screenshots/bsc_decision_tree.png"/>
</p>
* The finalized decision tree with 18 nodes. This tree was chosen has it had the best predictive capabilities. 

<p align="center">
  <img src="https://github.com/esaritepe/BabyCarSeat-Sales-Predictions/blob/main/screenshots/bcs_stats_table.png"/>
</p>
* A table showing the statistical analysis results featuring the MAE, RMSE, and correlation of all the tested models. As underlined in the table, the most reliable model was determined to be a tie between a 5-predictor Stepwise model and a 5-predictor Best Subset model. 

<p align="center">
  <img src="https://github.com/esaritepe/BabyCarSeat-Sales-Predictions/blob/main/screenshots/bcs_formula.png"/>
</p>
* The final regression model we suggested using price, education, age, advertising, and shelving location as predictors. 

Conclusion
----------
* A 5-predictor multilinear regression model using either stepwise or best subset selection was more reliable than the decision tree model, with a 12% reduced RMSE and 2% improved correlation. 
* Suggested a new linear regression model that would predict baby car seat sales based on the location characteristics of price, education, age, advertising, and shelving location. 

Contribution 
-------------
* This was a group project done with Jin Chen, Beom Ki Lee, and Sushant Varghese

