# GEOTAB_intersection_congestion

Intersections are the bottle necks of all traffic jams. In this project, the dataset is provided by GEOTAB, including intersection, month, hour of day, direction driven through the intersection, and whether the day was on a weekend or not. The task is to predict the waiting time and killing distance at each intersection.

Given the previous information, feature engineering is required to prepare the data in which some information are generalized and made applicable. The training data was fed to classic linear regression, random forest, XGBoost and catboost on a local machine. However, the limited computation capacity render the approach inefficient. Thus, the Google BigQuery ML was adopted.
