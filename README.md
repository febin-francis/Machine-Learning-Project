# Machine-Learning-Project

1. Load the dataset in Jupyter Notebook using pandas
2. Build a correlation matrix between all the numeric features in the dataset. Report the
features, which are correlated at a cut-off of 0.70. What actions will you take on the
features, which are highly correlated?
3. Build a new feature named LOB_Hike_Offered using LOB and percentage hike
offered. Include this as a part of the data frame created in step 1. What assumption are
you trying to test with such variables?
4. Create a new data frame with the numeric features and categorical features as dummy
variable coded features. Which features will you include for model building and why?
5. Split the data into training set and test set. Use 80% of data for model training and
20% for model testing.
6. Build a model using Gender and Age as independent variable and Status as dependent
variable.
• Are Gender and Age a significant feature in this model?
• What inferences can be drawn from this model?

8. Build a model with statsmodel.api to predict the probability of Not Joining. How do
you interpret the model outcome? Report the model performance on the test set.
9. Build a model with statsmodel.formula.api to predict the probability of Not Joining
and report the model performance on the test set. What difference do you observe in
the model built here and the one built in step 7.
10. Build a model using sklearn package to predict the probability of Not Joining. What
difference do you observe in this model compared to model built in step 7 and 8.
11. Fine-tune the cut-off value using cost of misclassification as a strategy. The cut-off
should help classify maximum number of Not Joining cases correctly.
12. Fine-tune the cut-off value using youdens index as a strategy. The cut-off should help
balance the classification of Joined and Not Joined cases.
13. Apply the cut-off values obtained in step 10 and step 11 on the test set. What
inference can be deduced from it?
