Summary:
                    1. We Have  Various Data to Prove a Company is Bankrupt or Not, Using Bankrupt as Target Variable With Various Continuous Data . We Have ,'bankrupt','liability-assets Flag','net Income Flag' Are Categorical Variables and Other Feature Variables.
                      2. Features Have Outliers Which Affect  Accuracy of the Model Hence Using Iqr We Find and Remove Outliers.
                       3.we Then  Used Different Tools to Check Null Hypothesis and Checking Relation Between Feature and Target Variable.such Anova , Ztest Check Null Hypothesis.
We Find in Anova Test['bankrupt','current_liability_to_equity is Not Affected Significantly by Bankruptcy Target Variable.
   Using Z Test Show How Much Standard Deviation Vary From Mean We Get Z =(-inf, 0.0
Showing a High Value of P Means Null Hypothesis Sustain.
                       4.we Checked  Correlation Matrix We 
Find Negative Correlation . Feature Inversely Proportional to Target Variable.
    4.now After Selection of Independent Variable Bankrupt and Single Dependent Variable .
     5.we Developed a Logistic Regression Model Selecting Features Against Bankrupt Variables. We Get 95% Accuracy With Logistic Regression. Such Way We Analyzing Effect of{ 'after-tax Net Interest Rate',
       'non-industry Income and Expenditure/revenue',
       'continuous Interest Rate (After Tax)', 'operating Expense Rate',
       'research and Development Expense Rate', 'cash Flow Rate',
       'interest-bearing Debt Interest Rate', 'tax Rate (a)',
       'net Value Per Share (B)', 'net Value Per Share (a)'] Upon a Bankrupt Categorical Variable.
6.we Use SMOT for Balancing Model and RFE
