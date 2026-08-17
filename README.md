# Firn Rheology Revealed by Contrasting Shear Regimes
## publication package

This is a preliminary repo containing data and code for the manuscript "Firn Rheology Revealed by Contrasting Shear Regimes publication". Our intent is to better document everything and archive it properly once the manuscript has been accepted. 

## Authors
Aslak Grinsted<sup>1</sup>, Nicholas Mossor Rathmann<sup>1</sup>, Johannes Freitag<sup>2</sup>, Josephine Lindsey-Clark<sup>1</sup>, Sune Olander Rasmussen<sup>1</sup>, Niels Fabrin Nymand<sup>1</sup>, Christine Schøtt Hvidberg<sup>1</sup>

<sup>1</sup> Physics of Ice, Climate, and Earth, Niels Bohr Institute, University of Copenhagen, Jagtvej 128, DK-2200 Copenhagen N, Denmark  

<sup>2</sup> Alfred Wegener Institute, Helmholtz Centre for Polar and Marine Research, Bremerhaven, Germany


## ENTRY POINT

If you want to play with these scripts, then your entry point should be 9_implications.ipynb 

(That will show you how everything is being used.)



## Desciption of files

| File                            | Description                                         | 
|---------------------------------|-----------------------------------------------------|
| bdot_regression_estimate.tif    | radar+topography based estimate of local accumation |
| EGRIP_backtrajectory.parquet    | data extracted along the back trajectory from EGRIP |
| S5-1hxct_backtrajectory.parquet | data extracted along the back trajectory from S5-1  |
| 9_implications.ipynb            | Code that reproduces figure 4. (*ENTRY POINT*)      |
| Density_S5_1_HXCT.txt           | HXCT density measurements for S5-1                  |
| egrip_ice_core_acc.parquet      | ice core derived accumulation rates (see fig2)      |
| steadystate_fit.parquet         | steady state a&b parameter fits (see fig3)          |
| 5_fit_spline.parquet            | non-steady state a&b parameter fits (see fig3)      |
| grinsted_firn_model.py          | many key functions describing the rheology          |


