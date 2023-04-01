# exxa-task
GSoC EXXA Test 2023 ML4Sci
The task was to create a simulated dataset of transit curves and use this data to train a classifier that determines whether or not a given transit curve shows the presence of a planet. 
I used "batman-package" to generate synthetic transit light curves data. 
I defined some physical and orbital properties of an exoplanet system. I had to adjust the input parameters several times before i got good transit curves in the dataset.
By using this method, i generated two datasets-one with 10,000 data points(to train the classifier) and another with 1000 data points (to test the classfier).
I chose a pre-trained model, support vector machine to try and predict whether a given transit curve shows the presence of a planet or no.
The AUC score for this model is 98.6 
