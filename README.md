This is a mini project based on Machine Learning.

The goal was to use past data to predict the house prices of Bangalore city. The data-set used for training & testing the data was obtained from 
Kaggle(https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data).

The project flow was: 
-> Analysing the data by various means like histograms, scatter-plots, correlation matrix etc.
-> Cleaning the data-set by removing some outliers, null values, irrelevant paramters etc.
-> Finally after cleaning the data-set, independent parameters were decided. The parameters used were(Location, BHK, number of Bathroom, Locality). The dependant 
   parameter was Price of the house.
-> Linear Regression from Scikit-Learn was used for the model. The data was split into a ratio of 80% and 20% for training & testing purposes.
-> Python was used to build the http server based on Flask framework and used nginx as a reverse proxy & to serve static files.
-> HTML5, CSS3 & JavaScript were used to build the front-end of the website.
