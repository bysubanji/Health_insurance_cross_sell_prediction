# Health_insurance_cross_sell_prediction

# PROBLEM STATEMENT
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

# APPROACH
Initially, imported the data set to carry out the descriptive analysis over the data set to comprehend the information of data available.

Cross-Checked for missing and repetition of values in the data set provided.

Exploring all the variables of the data set (such as Id, Age, Vehicle, vehicle age, etc) concerning opting for vehicle insurance, to determine the factors and understand factors affecting opting for vehicle insurance.

Used data visualization with different plots to explore the correlation between different variables.

Encoding of categorical columns and fitting the different models, we used the below algorithms:- Logistic Regression Random forest classifier XGB classifier

Then tuning into Hyperparameters and perfomance evaluation to identify best fit Model. 

# CONCLUSION
Customers of aged between 30 to 60 are more likely to buy insurance.  Youngsters under 30 are not intrigued by vehicle insurance. Reasons could be the absence of involvement, less awareness about insurance and they may not have costly vehicles yet.  Consumers with 1-2-year-old vehicles are more interested as compared to others. 

Consumers with less than 1-year-old Vehicles have very less chance of buying Insurance

Customers with Driving License have a higher chance of buying Insurance.  Customers with Vehicle_Damage are likely to buy insurance.  The variable such as Age, Previously_insured, Annual_premium is more affecting the target variable.  Comparing the ROC curve we can see that the Random Forest model performs better. Because curves closer to the top-left corner indicate better performance.
