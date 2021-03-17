# AbaloneRegression


### For this project, I used the Abalone Dataset to predict the number of rings an Abalone has given some features related to the size and weight. 

After cleaning the data, making new feature columns and transforming appropriately, I decided on a SGD Regressor model, which had an root mean squared error of ~2.1 and mean absolute error of ~1.5 on the entire set, which was in-line for how the model performed on the hold-out set.

I also observed that the predictions when the number of rings is large (>13) does rather poorly, and with lesser rings (<=13), does really well. Since only ~12% of the data overall had more than 13 rings, this model's performance is very strong on most of the data.

In exploration of the data, I expected to not get "great" results, meaning predictions that were within a few percentage points, and in looking at other projects on this data set, most had very similar RSME and MAE scores.
