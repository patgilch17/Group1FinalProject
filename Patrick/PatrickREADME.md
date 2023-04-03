## Available Data

In This folder you will find the rate of prescriptions for each county over a 4 year period.  Ideally you will find this in the main branch of our project with the paragraph below included in our main ReadMe.

One of the many dependent factors on our analysis we are hoping to include is that of the amount of opioids prescribed in each county.  The simple idea being that one major talking point of the opioid crisis in the US is that it is in part due to the number of prescription opioids used as painkillers in medicine.  These rates can be found on the [CDC website](https://www.cdc.gov/drugoverdose/rxrate-maps/index.html) and essentially say the number of prescriptions filled per 100 people over the course of the year.


### Patrick's Info for my slide(s)
I was responsible for our Random Forest model, which we would use to try and determine if we the model could identify if a county would be in the to 25% by crude rate based on our features.  Futhermore, we wanted to use the Random Forest model to identify which features would be most significant.

I would talk us through the results
![Random Forest Results](Resources/RandomForest.png)

The importance of the included features can be seen here
![Feature Importance](Resources/FeatureImportance.png)

The Receiver Operating Characteristic Curve and the AUC score can be seen here
![ROC Curve](Resources/AUCPositiveClassifier.png)

Because categorizing the data essentially means we have one "Class" with less results I tried out using the SMOTEEN process in conjunction with the Random Forest Model to generate more data.  The model wasn't quite as good as can be seen below.
![SMOTEEN Results](Resources/RandomForestSmoteen.png)