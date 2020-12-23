# My-first-ML-project
Blight ticket prediction.
This project is a real life situation happended in Detroit a city in Michigan.Every year the Detroit city issues fines in millions of dollars to people who allow the property to remain in deteroitaed condition and many of these remain unpaid.Blight ticket is the ticket issued as fine to residents who violate maintanance of properties.My target was to predict wheather the blight ticket will be paid on time or not.

So in order to do that,two data sets have beem loaded and analyzing the features/columns we can see several columns that are not necessary for our training and includes some nan and unique values  which has to be removed.The data cleaning has been done by analyzing the importance of features that are related to the target variable

Here our target variable is called as "Compliance".Our target is to predict this compliance.
Grid searchCV method and random forest regressor has been used to predict the compliance.
Here trainig the model is based on types of violations commited by the people(in data).
The accuracy obtained is thus calculated using roc_auc_score evaluation metric.
