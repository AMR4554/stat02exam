Summary:
                    1. We have  various data to prove a company is bankrupt or not, using bankrupt as target variable with various continuous data . We have ,'Bankrupt','Liability-Assets Flag','Net Income Flag' are categorical variables and other feature variables.
                      2. Features have outliers which affect  accuracy of the model hence using IQR we find and remove outliers.
                       3.we then  used different tools to check null hypothesis and checking relation between feature and target variable.such ANOVA , ZTEST check null hypothesis.
We find in anova test['Bankrupt','Current_Liability_to_Equity is not affected significantly by bankruptcy target variable.
   Using Z TEST show how much standard deviation vary from mean we get z =(-inf, 0.0
Showing a high value of p means null hypothesis sustain.
                       4.we checked  correlation matrix we 
Find negative correlation . feature inversely proportional to target variable.
    4.now after selection of independent variable bankrupt and single dependent variable .
     5.we developed a logistic regression model selecting features against bankrupt variables. We get 95% Accuracy with logistic regression. Such way we analyzing effect of{ 'After-tax net Interest Rate',
       'Non-industry income and expenditure/revenue',
       'Continuous interest rate (after tax)', 'Operating Expense Rate',
       'Research and development expense rate', 'Cash flow rate',
       'Interest-bearing debt interest rate', 'Tax rate (A)',
       'Net Value Per Share (B)', 'Net Value Per Share (A)'] upon a bankrupt categorical variable.
6.we use SMOT for balancing model and RFE
