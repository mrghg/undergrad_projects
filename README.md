# Project ideas and materials for University of Bristol final year project students

Please contact Matt Rigby to discuss project ideas

To run the code in this repository, you'll need to have a working Python distribution on your system. If you are installing this yourself, I recommend using the [Anaconda distribution](https://www.anaconda.com/download/). 

As part of Anaconda, you will download the [conda package manager](https://docs.conda.io/projects/conda/en/latest/index.html), which you can use to install and manage python libraries. There is a GUI, which you can use to manage your Python environments, or you can use the command line. For example, to install the xarray package, you can type:

```
conda install xarray
```

### NetCDF files and xarray

Our group uses the [netCDF](https://www.unidata.ucar.edu/software/netcdf/) file format extensively. NetCDF is a self-describing binary format. It is extremely useful for atmospheric data, but it does take some time to learn. Please familiarise yourself with the documnetation.

To interact with netCDF files in Python, the [xarray](https://docs.xarray.dev/en/stable/index.html) library is extremely useful. Xarray provides [pandas-like](https://pandas.pydata.org) tools for N-dimensional data (Pandas is primarily for tables, like you'd use Excel for).

### Test files

Some files are included in the ```data``` folder of repository, to demonstrate key concepts. However, they are only small subsets of the real data and model outputs. You will be provided with access to the original dataset when the project begins.