# codefundo++
## Predict Natural Disasters caused by Tectonic Plate Movement

Surface of the Earth cannot be considered as a single structure of mass, but a combination of many plates. These plates continuously slide within the mantle, inside the Earth. These movements are extremely slow and distributed over millions of years. However, sometimes this shift in plates might be abrupt, causing Natural Disasters like Earthquakes, Volacanoes and Seismic Sea Waves. 

Keeping this concept in mind, we have come up with a methedology of predicting these disasters. Peter Bird, from University of California, in 2003 published a dataset on Tectonic Plates. We plan to take this data as an input to our model. Along with this, we would exact the occurrences of Earthquakes and Tsunamis from Kaggle's dataset called "Significant Earthquakes 1965-2016" and "Tsunami's History".

Finally, using this information, we want to predict the location and time of these disasters.

To get into further details, our initial task would be to map the three datasets. The first dataset consists of the following attributes : 

1.PlateBoundIdentifer,
2.PlateBoundContinuity,
3.StartLong,
4.StartLat,
5.FinalLong,
6.FinalLat,
7.StepLength(km),
8.AzimuthCenter,
9.VelocityLeft,
10.VelocityAzimuth,
11.VelocityDivergent,
12.VelocityRightLateral,
13.Elevation,
14.SeafloorAge,
15.StepClass,
16.StepContinuity,
17.Orogen

The second dataset consists of the following attributes:

1.Date,
2.Time,
3.Latitude,
4.Longitude,
5.Type,
6.Depth,
7.Depth Error,
8.Depth Seismic Stations,
9.Magnitude,
10.Magnitude Type that can be based on any of the following:
  -ML: Local (Richter) magnitude
  -MS: surface wave magnitude scale
  -MB (Mb): Body wave magnitude scale
  -MW (Mw): Moment magnitude scale
  -MD (Md): Duration magnitude/signal duration
11.Magnitude Error,
12.Magnitude Seismic Stations,
13.Azimuthal Gap,
14.Horizontal Distance,
15.Horizontal Error,
16.Root Mean Square,
17.ID,
18.Source,
19.Location Source,
20.Magnitude Source,
21.Status

The Thrid dataset consists of the following attributes: 
1.Year,
2.Month,
3.Day,
4.Hour,
5.Minute,
6.Second,
7.Event Validity,
8.Cause Code,
9.Focal Depth,
10.Primary Magnitude,
11.Country,
12.State,
13.Location Name,
14.Latitude,
15.Longitude,
16.Region Code,
17.Maximum Water Height

These would be mapped based on the values of longitude and the latitude, as they act as common features to all the datasets.

Once the data is complete, we would divide it into a 80:20 ratio of training to testing data. Futher, training data would be divided into 80:20 ratio of training set to validation set. We would train the data on various Machine Learning models and validate upon our data, and finally present our predictions about the occurrences of earthquakes and tsunamis based on the findings in our testing data.
