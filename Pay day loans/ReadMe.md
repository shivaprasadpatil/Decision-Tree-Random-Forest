## Practice Exercise for Decision Trees and Bagged Tree Ensembles
<ol>
<li>Decision Tree based models can be used for regression problems as well. Use grid search cv [Not RandomSearchCV] to tune a single decision tree for interest rate prediction problem and compare this best tree's performance with linear regression model with l1 penalty </li>
<br></br>
<li> Payday Loans are high risk short term lending financial products and its very important to asses risk of payment default. Use dataset "paydayloan_collections.csv" to build a model whether repayment will be successful or not. All variables and values have been masked in order to hide sensitive information about consumers.
<br></br>
Use RandomForest and ExtraTreeClassifier to build your model and compare their performance on test data. Prepare partial dependence plots for 4 most important variables for both RandomForest and ExtraTrees</li>
<br></br>
<li> RandomSearchCV uses default score of the algorithm for parameter selection. Consider "emission.csv" which contains first one year average emission data for 10000 vehicles along with measurements of their various tehcnical specifications. 
<br></br>
Build a model for ppm emission  as function of tehcnical specifications of vehicles. Use average absolute error [Instead of squared error loss] for parameter selection in RandomSearchCV with RandomForest Regressior.</li>
</ol>
