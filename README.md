# Salary Prediction Based on Years of Experience Using Linear Regression in Excel

This project ,we predict the salary of an employee based on their years of experience using simple linear regression in Microsoft Excel.
Linear regression is a statistical method used to model the relationship between a dependent variable and an independent variable.
In this project:
- X(Independent Variable) represents Years Of Experience
- Y(Dependent Variable) represents the salary

### Linear Regression Model
![RegressionModel](https://github.com/njerimuriithi/Salary-Prediction/blob/10e708ca26b772408234bb2e68eaae9c1e5f53a6/Regression%20Model.png)

  The linear regression Formula is:
  
      > Y = b₀ + b₁x
      
  - Y = Dependent Variable (salary)
  - b₀ = Intercept (The salary value when the Years of Experience is 0)
  - b₁ = Slope (Rate of change in salary per year of experince)
  - X = Independent Variable (Years of experience)

  Estimated Model Salary Calculation:
  
   >  Salary = 8731.9x + 28860


## Model Summary
![Summurary Output](https://github.com/njerimuriithi/Salary-Prediction/blob/10e708ca26b772408234bb2e68eaae9c1e5f53a6/Summary%20Output.png)
 #### 1.  R Square(R2) = 0.96
Indicates that 96% of the variation in salary is explained by years of experience, showing a strong model fit.

#### 2. Slope(8731.9)
 On average the salary increases by approximately 8732 for each additional year of experience
 
#### 3. Intercept(28,860)
The predicted salary for an employee with 0 yrs of experience

#### 4. Significance F (p-value ≈ 1.23 × 10⁻²⁵)

The extremely small p-value leads to rejection of the null hypothesis(no relationship between years of Experience and Salary), confirming a statistically significant relationship between years of experience and salary

#### 5. Standard Error
Measures the average deviation of observed salaries from the regression line, indicating prediction accuracy.

## Conclusion
The results confirm that years of experience is a strong and statistically significant predictor of salary.
This project highlights how Excel can be effectively used for regression analysis and salary prediction.




  

