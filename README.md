# Description

Get annual primary productivity mg C m<sup>-2</sup> yr<sup>-1</sup>
from latitude, longitude and year.
Annual primary productivity is computed from  data automatically downloaded from http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.vgpm.m.chl.m.sst.php.
This input data was produced with the VGPM algorithm of Behrenfeld, MJ, PG Falkowski:  Photosynthetic rates derived from satellite-based chlorophyll concentration, Limnology and Oceanography, 42, 1-20, 1997.

# How to use

Prerequisite: Anaconda for Python 3. See https://www.anaconda.com/distribution/

`cd my_directory_containing_annual_pp.ipynb`

`conda create -n hdf -c conda-forge ipython jupyterlab matplotlib numpy pandas pyhdf pytables pywget scipy python=3.7`

`conda activate hdf`

`jupyter notebook`
