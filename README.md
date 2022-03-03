# Forecasting-Challenge
This repository contains code for predicting the water level of the Rhine using sensor data in Kaub + additional data of the DWD with the help of neural networks.

## Install
In order to install all the dependencies via conda use the command:
> conda env create --name envname --file=environment.yml

## Files

In the following, I will provide a short summary about the individual files. The main contributions are the files: analysis.ipynb and network-DWD.ipynb.

* __analysis.ipynb__: Analysis and visualization of the dataset.
* __network-DWD.ipynb__: Prediction on the data using additional data from Deutscher Wetterdienst (DWD)
* __duplicates.ipynb__: Shows the duplicate/missing values in the original and first updated values
* __sarima.ipynb__: Prediction using SARIMA
