# ensemble

About data used:
Historical data for 45 stores located in different regions.  - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

Tasks done:
1. Exploratory data analysis and visualization.
2. Data preparation for machine learning models.
3. Development of DecisionTreeRegressor model to predict weekly sales.
4. Development of RandomForestRegressor model to predict weekly sales, used RandomizedSearchCV and GridSearchCV to find optimal values of parameters.
5. Development of GradientBoostRegressor model to predict weekly sales, used GridSearchCV to find optimal values of parameters.
6. Stack (ensemble) the regressors in 3. 4. and 5. to predict the weekly sales
