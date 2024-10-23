# Performance-Analysis-National-Water-Model
This repository is for the calculation of performance metrics for NWM data. 

The NWM_data_download.ipynb is to download the NWM retrospective data for NWM version 2.1 and 3.0 from the amazon bucket. 
The NWM_data_download_short_range file is to download the short-range data from the google archive. USGS data can be downloaded from the USGS_data_download file. 
User can download data either from the NWIS or the USGS API. 

The folder 1979 contains example NWM retrospective 3.0 data and the folder usgs_data_1979_2023_parquet folder contains USGS data to run and test the scripts. The consolidated_annual_min_retro_3 file contains the discharge data for threshold values.
