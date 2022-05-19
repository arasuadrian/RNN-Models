# RNN-Models
This repository contains LSTM and RNN models.
The data for use in the models is available at https://github.com/pangeo-data/WeatherBench.
The data is avaiable in netCDF4 format.
Use the nctocsv convertor to store the data in csv format.
The model code requires that the input files are in csv format.
The code can also be edited to directly convert the nc files to pandas dataframe.
For ease of use, the convertor and models are split into two notebook files.
The LSTM and RFR models in the repository readily nowcasts temperature of the next hour.
The code can be edited to perform short range forecast.
