# Grinsted firn model


This repository is a small collection of selected scripts and data files for the manuscript with the working title:
"Firn Rheology from Contrasting Shear Regimes" by Grinsted et al. 

Our intent is that contents of this repository will be properly documented and archived in zenodo or similar upon acceptance of the manuscript.


## Description of files: 

# grinsted_firn_model.py
A set of utility functions for the GM97

# 9_implications.ipynb  
A forward flowline density model tracking z_closeoff and $\Delta age$. This code reproduces the 


# 5_fit_spline.parquet
This file has the $a(\rho)$ and $b(\rho)$ table from our flowline inversion. 

# steadystate_fit.parquet
This file has the $a(\rho)$ and $b(\rho)$ table from our steady state inversion. 

# bdot_regression_estimate.tif
This is the local accumulation rate map derived from a DEM+radar regression. 

# EGRIP_backtrajectory.parquet & S5-1hxct_backtrajectory.parquet
A table containing 2000 years worth of backtrajectory data. t,x,y,e1,e2 ... 

# egrip_ice_core_acc.parquet
This is the accumulation curve derived from the timescale and density curve at EGRIP. With a simple nye like thinning correction. Beware: uncertainties/errors in the thinning correction accumulates back in time.
 
# Density_S5_1_HXCT.txt
HXCT based densities for the S5-1 shear margin core. 


 