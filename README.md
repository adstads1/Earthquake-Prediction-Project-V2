# Earthquake Prediction Project

#### A full data pipleine that predicts the magnitude and coordinates of the next earthquake.

Within this project I have created a local Data Engineering infrastructure using:
* Jupyter Lab - For scheduling daily jobs to retreive up to date Earthquake API results.
* MySQL - To store the historical earthquake dataset and predicted earthquake information.
* Power BI - To extract the data from MySQL database and visualise additional trends and patterns of earthquakes.

Within this Jupyter notebook, I have gone through the Data Science pipeline and also implemented a Machine learning model. <br> Within this notebook, for the prediction of an earthquake, I have used:
- A Standard scaler to scale the features to unit variance.
- A Multivarient Linear Regression model with depth and time as the features.
- Simple evaluation techniquestion which will be useful for hyperparameter tuning.

More information about the project can be read in the [notebook](Earthquake_Analysis.ipynb).

**PCA: The model used in this project isn't highly accurate but is a good starting project to develop upon.**

[Here is the report for curiosity](Earthquake_pbi.pdf)
