# DSC520-Verifying-Assumptions
 An assignment for DSC520 at GCU that focused on verifying that a linear regression model does not violate the assumptions of linear regression.

Check out the full report [here.](https://github.com/jhould007/DSC520-Verifying-Assumptions/blob/main/Verifying%20Assumptions.ipynb)

# Assignment Instructions
Regression takes data represented as variables and a prediction and tries to find the mathematical relation between them. Linear regression and regression analysis are some of the methods through which data is used for predictions, forecasting, inferring relationships, or error reduction. Any type of regression makes assumptions about the data. However, good results will not be obtained if the assumptions are not verified. Therefore, for a successful regression, assumptions must be validated through statistical testing and solutions implemented to tackle any violations if present.

For this activity, perform the following:
1. Access the repository and use the dataset provided by the instructor.
2. Describe a predictive model you could build using this dataset and present it, including the analysis of the residuals.
3. Verify the assumptions of the linear regression using plots. Explain each test, comment on the code, and interpret the test result for: a) Linear relationship: Each predictor variable xi and the outcome variable y. Use the plot function and which=1; b) Independence: The residuals are independent. Use durbinWatsonTest function in the car package; c) Homoscedasticity: The residuals have constant variance at every level of x. Use plot function and which=3; and d) Normality: The residuals of the model are normally distributed. Use the plot function and which=2.
4. Verify the assumption of homoscedasticity computationally using the Non-Constant Variance Score (NCV) test (ncvTest function). Explain the test, the R code, and interpret the test results. Explain the relationship between NCV and the Durbin-Watson test.
5. Assess the presence of significant outliers and explain their potential impact. Use the plot function and which=5, and the Cook distance.
6. Explain how you would mitigate the impact of the outlier. Then, implement measures to mitigate the impact of outliers (e.g., removal or other transformations of the data).
7. Discuss what other tests/transformations you could use if there are no outliers. Could a log transformation for reducing skewness be used? Explain.
8. Repeat steps 4-5, using the "cleaner" dataset.
9. Test collinearity using the Variance Inflation Factor. Use the vif function in R or Python.
10. Assess the overall validity of the regression model and present your final assessment regarding its readiness and suitability for making predictions.
11. Given your analysis, describe the recommendations you would make to a researcher intent on using this data in a multiple linear regression model.

Then, submit a professionally written and formatted software-based technical report. Make sure the documentation contains the code, relevant plots, your analysis, and the appropriate citations and references.

While APA style is not required for the body of this assignment, solid academic writing is expected, and documentation of sources should be presented using APA formatting guidelines, which can be found in the APA Style Guide, located in the Student Success Center.

This assignment uses a rubric. Review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion.

You are not required to submit this assignment to LopesWrite. 
