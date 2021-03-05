# Capstone-Project-3
Demand Prediction



Demand_Prediction_Project
Welcome to "Demand Prediction Project".

As you know recently, free or affordable access to bicycles has been provided for short-distance trips in an urban area as an alternative to motorized public transport or private vehicles. Thus, it is aimed to reduce traffic congestion, noise and air pollution.

In this project, the goal is to predict the number of future bike shares given the historical data of London bike shares. So this case should be handled as a time series problem with Bidirectional LSTM.

In order to achieve this goal, you will make predictions with LSTM, unlike the machine learning algorithms you have applied before. Long short term memory (LSTM) is an artificial repetitive neural network architecture used in the field of deep learning. Unlike standard feed forward neural networks, LSTM has feedback links. It can process not only single data points but also entire data series.

Before diving into the project, please take a look at the Determines and Tasks.

Features

timestamp - timestamp field for grouping the data
cnt - the count of a new bike shares
t1 - real temperature in C
t2 - temperature in C “feels like”
hum - humidity in percentage
wind_speed - wind speed in km/h
weather_code - category of the weather
is_holiday - boolean field - 1 holiday / 0 non holiday
is_weekend - boolean field - 1 if the day is weekend
season - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.
Initially, the task of discovering data will be waiting for you as always. Recognize features, detect missing values, outliers etc.

Review the data from various angles in different time breakdowns. For example, visualize the distribution of bike shares by day of the week. With this graph, you will be able to easily observe and make inferences how people's behavior changes daily. Likewise, you can make hourly, monthly, seasonally etc. analyzes. In addition, you can analyze correlation of variables with a heatmap.

In the Pre-Processing task after train test split and robust scaling, the challenge for you will be to divide the data into time steps and transform it into a three dimentional numpy array.

Then in the model building task, build your model appropriate and compare the train and validation losses using a graph.

When making prediction, you will need to do the inverse transform process to get a true error score. Otherwise, the results you get with scaled target variables may mislead you.

Finally, Visualize how well your model's predictions match the actual values of the test data and also calculate error scores.
