# Toolkit on Channel Island variable observations

This repository will be housing the three notebooks that will include information on:
- How to map the area on variable of interest
- Creating a time series for certain timeframe for variable of interest
- Creating a vertical profile to view changes in variable of interest

## Creating the environment

In order to work with this data, it is important to have the correct packages and dependencies in your environment to properly access the data. These are the steps we recommend you take to create the correct environment.

1. Open up the terminal and type this command:
    `conda create -n your_env_name -c conda-forge dask distributed ipython netcdf4 xarray intake-esm aiohttp`
   *Note*: Make sure to replace the phrase `your_env_name` with an environment name of your choosing before running this command
2. After running that command once it has finished running, run this next command to activate your environment:
    `conda activate cmip6`

At this point, you will have successfully created your environment and you can start running the code featured on these notebooks. If you run into any issue with any of the packages not being properly installed, we recommend running the command `pip install package_name`.
*Note*: make sure to replace the phrase `package_name` with the package that you are missing to ensure correct installation of that package.
