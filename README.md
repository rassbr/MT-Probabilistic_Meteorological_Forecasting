# MT-Probabilistic_Meteorological_Forecasting
This repository contains the codes developed during an internship in Airbus and used in the Master Thesis, also in this repository.

# Airbus Copyright
All the code here is owned by Airbus

# What is on the code?

## 01-Request_NOAA_data-GFS_GENS.ipynb
This file contains a script capable of download GFS or GENS data from NOAA's website. Some smaller modifications may be necessary to adapt it to your necessity (days, forecast hours, etc).

## 02a-grib_Parser-to-PANDAS.ipynb 
A code capable of parsing the .grib data download using the previous notebook. The data will be parsed to a DataFrame (which is not optimal depending on how you intends to use the data).

## 02b-grib_Parser-to-Matrix_numpy.ipynb
Similar to the previous one, but the resulting data will be a numpy matrix.

## 03a-data-extracting_and_visualizing.ipynb
Code dedicated to visualize the data punctually.

## 03b-Analysis of Dependence.ipynb
A brief analysis of how the value of the wind is dependent from the value close to it. It evaluated de dependencies in space and also in time.

## 04a-data-verifying_punctual_metric(slow).ipynb
Application of the punctual metric and evaluation of some distributions using it (Gaussian, KDE, Histogram and best fitting). (slow) -> since it uses DataFrame in a non-efficient way, the calculations are slow.

## 04b-data-verifying_CRPS(slow).ipynb
Application of the CRPS metric and evaluation of the Gaussian distribution and the Histogram. (slow) -> since it uses DataFrame in a non-efficient way, the calculations are slow.

## 05-simplified_model_validation-sigma_non-variant_in_time.ipynb
Application and analysis of the simplified model, i.e., $\sigma$ constant in time. Evaluation of the results using CRPS.

##

##
