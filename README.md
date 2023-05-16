# exxa-task
EXXA Test 2023:-
The task was to create a simulated dataset of transit curves and use this data to train a classifier that determines whether or not a given transit curve shows the presence of a planet. 
I used "batman-package" to generate synthetic transit light curves data by defining some physical and orbital properties of an exoplanet system. I had to adjust the input parameters several times before i got good transit curves in the dataset.
By using this method, I generated two datasets-one with 10,000 data points(original_simulated_data, to train the classifier) and another with 1000 data points (new_test_data, to test the classfier).
I chose a pre-trained model, support vector machine to try and predict whether a given transit curve shows the presence of a planet or no.
The AUC score for this model came out to be 98.6 
