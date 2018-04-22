# Traffic-Congestion-Prediction
In pattern recognition, the k-nearest neighbor algorithm (k-NN) is a non-parametric method used for classification and regression.
Within a city, the travel time from point A to B depends on many dynamic factors along with the demographics. Even within each hour
of the day, there can be variations in travel time based on busy and non-busy hour traffic. Also, the day of the week plays a role,
as the weekends will witness faster travel times due to low traffic density. Apart from this, thereare also some environmental conditions 
such as weather conditions and temperature that indirectly affect the travel time.
Data that affects travel time: 
1. Time of the day
     The travel time is largely dependent on this as during busy hours the traffic densely on the city roads is at its peak.
2. Day of the week
     Weekdays always witness more traffic density due to the rush of office commuters as compared to weekends.
3. Weather conditions
     Harsh weather conditions can affect road and public infrastructure so this has an adverse impact on travel time.
4. Temperature
     Extreme temperature tend to keep people indoors which means less traffic density and faster travel.
Data to the algorithm is provided by two different sets of data. TRAIN_SET and TEST_SET are the training set to train our kNN algorithm and testing test respectively.
The training set consists of Date,Zone,Day,CodedDay,CodedWeather,Temperature,RealTime.
The testing set consists of Date,Zone,Day,CodedDay,CodedWeather,Temperature.
The repository consists of TRAIN_SET.csv -Training set, TEST_SET.csv- Testing set,WeatherCodes.txt -Numeric codes for all weather conditions and knn_tensor.py - Python demo program using the tensorflow library to generate prediction.
