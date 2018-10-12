# codefundo++
# Predict Natural Disasters caused by Tectonic Plate Movement

Surface of Earth cannot be considered one structure of mass but is a combination of plates. These plates are continuously sliding in the mantle inside Earth. These movements mostly are very slow and distributed over millions of years. But sometimes they might move abruptly with respect to each other and cause Natural Disasters like Earthquakes, Volacanoes and Seismic Sea Waves. 
Keeping this concept in mind, we have come up with a methedology of predicting natural disasters. Peter Bird, from University of California, in 2003 published a dataset on Tectonic Plates. We plan to take this data as an input to our model. Along with this, the exact occurrences of Earthquakes and Tsunamis is extracted from Kaggle datasets.
Finally, using this information, we want to predict the location and time of these disasters.

To get into further details, our first aim would be to map the two datasets. The first dataset consists of the movement, the speed at which at the tectonics plates moved, the amount of disctance covered etc (All these attributes are present in the data published by Peter Bird) with the occurrences of earthquakes and tsunamis. We plan to do this mapping based on the longitude and the latitude that are present as common attributes in both the datasets. 

Once the datasets are combined, we would devide the dataset into 60:30:20 ratio of training to testing data. Further, we would divide the 70% of the training data into two sge
