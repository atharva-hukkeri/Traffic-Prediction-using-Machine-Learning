## Traffic-Prediction-using-Machine-Learning
A research-based project where a model of traffic congestion prediction was constructed by using machine learning classification algorithm - random forest and Support Vector  Regression.<br>

## About Dataset
📌 Date: The Date Column contains the date on which the data were recorded in the format DD/MM/YYYY.<br>
📌Day: The Day Column contains the weekday on which the data was collected. This is done to make the dataset more usable in terms of predicting the likelihood of traffic dependent on what day of the week it is.<br>
📌Coded Day: Each day of the week is assigned a code number by the coded day. Because we are not forced to write string functions for converting the given days to codes, predicting traffic depending on the day is considerably easier. The following are the day codes: -Monday - 1 Tuesday - 2 Wednesday - 3 Thursday - 4 Friday - 5 Saturday - 6 Sunday – 7<br>
📌Zone: This column contains the zone number for which traffic data is collected. The weather in this column has been coded. This is based on a variety of typical weather conditions. The amount of traffic fluctuates depending on the weather in each zone. This covers factors such as humidity, mist, visibility, and precipitation, among others.<br>
📌Temperature: This column contains the temperature for the given zone on a given day. Temperature has a significant impact on traffic forecasting.<br>
📌Traffic: This is the column that serves as the training dataset as well as a predictor. This column's traffic is coded on a five-level scale. The following are the levels: -1 - Less than 5 cars. 2 - 5 to 15 cars. 3 - 15 to 30 cars. 4 - 30 to 50 cars. 5 - More than 50 cars.<br>

## Performance Comparison
### Accuracy using Random Forest:<br>
Error = 13.42 %<br>
Accuracy= 86.58 %<br>
### Accuracy using Support Vector Regression:
Error = 12.16 %
Accuracy= 87.84 %
