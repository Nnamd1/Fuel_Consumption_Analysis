FUEL CONSUMPTION ANALYSIS(PREDICTION ON CO2 EMISSIONS FROM VEHICLES USING MULTIPLE REGRESSION TECHNIQUES)
An Exploratory Data Analysis Performed by Nnamdi Leonard

-------------------------------------------------------------------------------------------------------------------

Order Of Execution:
- Business Requirement
- Importation of required Python Libraries and dataset.
- Simple Linear Regression Technique and Conclusion
- Multiple Linear Regression Technique
- Polynomial (Non-Linear) Regression Technique

-------------------------------------------------------------------------------------------------------------------
BUSINESS REQUIREMENT

For a vehicle whose engine size is 2.4, predict the corresponding Co2 Emission using the historical data as given.

-------------------------------------------------------------------------------------------------------------------
DETAILS
-------------------------------------------------------------------------------------------------------------------

Simple Linear Regression Technique and Conclusion: 

- Called the required variables (both independent and dependent) and performed a quick descriptive analysis of the 
  data; also did a visualisation to depict how these variables interact with each other. 

- Plotted a scatter plot for each independent variable against the dependent variable (Co2 Emissions), in order to
  confirm it's linearity.

- In order to create a regression model, I first masked my data into a training and test portions to evaluate the
  data validation; with the training data having the bigger chunk of the dataset(80%) 

- Created the model by first importing the linear_model tool from the Scikit-Learn library, and then mapping my
  trained independent and dependent variables to build the model that predicts the intercept and Coefficient(gradient)

- Solved for the Co2 emissions of the vehicle using the predicted intercept and coefficient, and also plotted a 
  fitting line in the scatter plot graph.

- Tested the validation of my data by using the rest of the data (Train-Test Split method), by calculating the 
  Mean Absolute Error/Residual Error, Mean Squared Error and the R-Squared Score.


-------------------------------------------------------------------------------------------------------------------
Multiple Linear Regression Technique:

- Steps undergone in the Simple Linear Regression Technique is also similar with few exceptions; The trained and tested 
  masked data includes multiple independent variables that has an impact on the effect of the dependent variable. 

-------------------------------------------------------------------------------------------------------------------
Polynomial (Non-Linear) Regression Technique:

- Steps undergone in the Simple Linear Regression Technique is also similar with few exceptions; Before training and
  testing the data, the independent variables was first transformed to polynomials in degree 2 by importing PolynomialFeatures
  from the sklearn.preprocessing library.


THANKS FOR YOUR TIME
