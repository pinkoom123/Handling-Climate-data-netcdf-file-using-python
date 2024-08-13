# Handling-Climate-data-NetCDF-file-using-python
This is a step-by-step way of handling climate data such as  rainfall(Chirps) and temperature(ERA 5) NetCDF files.Using Python libraries such as xarray, matplotlib. cartopy, etc necessary to handle the climate data.
1. The code begins by importing essential Python libraries such as `xarray` for handling climate datasets and `cartopy` for geospatial plotting. 
2. It loads climate data (rainfall and temperature) from NetCDF files into variables using the `xarray` library, which provides easy access and manipulation of the data.
3. Missing values in the datasets are identified and counted to ensure data quality before further analysis.
4. The data is filtered for the period between 2009 to 2020 and then grouped by year to calculate annual averages for both rainfall and temperature.
5. Spatial plots of annual rainfall and temperature over Ghana from 2009 to 2020 are generated using `cartopy`, highlighting the variations across different years.
6. The code also calculates and plots the mean annual and monthly rainfall and temperature averages for the entire period (1991-2020) and extracts and visualizes data for specific locations within Ghana.
