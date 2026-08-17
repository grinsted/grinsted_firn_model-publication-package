# Firn Rheology Revealed by Contrasting Shear Regimes

## Publication package

This repository contains data products and code accompanying the manuscript:

**Grinsted et al., "Firn Rheology Revealed by Contrasting Shear Regimes"**

This is a preliminary publication package prepared for the review stage. The repository will be further documented and archived with a persistent identifier after manuscript acceptance.

## Authors

Aslak Grinsted<sup>1</sup>, Nicholas Mossor Rathmann<sup>1</sup>, Johannes Freitag<sup>2</sup>, Josephine Lindsey-Clark<sup>1</sup>, Sune Olander Rasmussen<sup>1</sup>, Niels Fabrin Nymand<sup>1</sup>, Christine Schøtt Hvidberg<sup>1</sup>

<sup>1</sup> Physics of Ice, Climate, and Earth, Niels Bohr Institute, University of Copenhagen, Jagtvej 128, DK-2200 Copenhagen N, Denmark

<sup>2</sup> Alfred Wegener Institute, Helmholtz Centre for Polar and Marine Research, Bremerhaven, Germany

## Entry point

The recommended starting point is:

`9_implications.ipynb`

This notebook shows how the firn model is used and reproduces the implication experiments shown in Fig. 4 of the manuscript.

## Description of files

| File | Description |
|------|-------------|
| `bdot_regression_estimate.tif` | Radar- and topography-based estimate of local accumulation |
| `EGRIP_backtrajectory.parquet` | Data extracted along the back trajectory from EGRIP |
| `S5-1hxct_backtrajectory.parquet` | Data extracted along the back trajectory from S5-1 |
| `9_implications.ipynb` | Code that reproduces Fig. 4. **Recommended entry point** |
| `Density_S5_1_HXCT.txt` | HXCT density measurements for S5-1 |
| `egrip_ice_core_acc.parquet` | Ice-core-derived accumulation rates used in Fig. 2 |
| `steadystate_fit.parquet` | Steady-state estimates of the rheological parameters `a` and `b` shown in Fig. 3 |
| `5_fit_spline.parquet` | Flowline-inversion estimates of the rheological parameters `a` and `b` shown in Fig. 3 |
| `grinsted_firn_model.py` | Core functions describing the firn rheology and model calculations |

## Notes

The repository is intended to make the main analysis steps and manuscript figures transparent during review. Some scripts and data products may be reorganized before final archival.

