# Sustainability
A solar power generation company wants to optimize solar power production and needs the prediction model to predict the
Clearsky Global Horizontal Irradiance(GHI), DNI, DHI. The data is ten years at an interval of every 30 mins with the following data points:

['Year', 'Month', 'Day', 'Hour', 'Minute', 'Temperature', 'Clearsky DHI', 'Clearsky DNI', 'Clearsky GHI', 'Cloud Type', 'Dew Point', 'Fill Flag', 'Relative Humidity', 'Solar Zenith Angle', 'Surface Albedo', 'Pressure', 'Precipitable Water', 'Wind Direction', 'Wind Speed']

# Evaluation
What is the Metric In this competition? 
The submission will be evaluated using the Mean Square Error. One can use sklearn.metrics.mean_squared_error to calculate the same

How to Generate a valid Submission File
Sklearn models support the predict() method to generate the predicted values
The participant should submit a .csv file with exactly  17,520 rows with 3 column ['Clearsky DHI', 'Clearsky DNI’,'Clearsky GHI']. 

# Data
https://machinehack.com/hackathon/wipro_sustainability_machine_learning_challenge/data

# Branch set up
+ Main branch has the latest code details
+ Branches with version<number> (version1,version2,etc) keeps track of changes 
+ for eg: branch:version1 is the basic skeleton, branch:version2 gives reasonable output etc
