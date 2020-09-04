# Repo for Chapter 4 of my PhD thesis, dealing with bivariate models

This repo extends the publication and repo of the paper 'Global hierarchical 
models for wind and wave contours: Physical interpretations of the dependence 
functions' by A. F. Haselsteiner, A. Sander, J.-H. Ohlendorf and K.-D. Thoben.

The repo contains the following things:
 * The used datasets (folder 'datasets')
 * Python files to reproduce the analysis
   * compute_contours_datasets_abc.py for the sea state models
   * compute_contours_datasets_def.py for the wind-wave state models
 * The coordinates of the computed environmental contours (folder 'contour-coordinates')

## Download and use the repository
To download this repository type
```console
git clone https://github.com/ahaselsteiner/2020-dissertation-bivariate-models.git
```

Then install the required Python packages by typing
```console
pip install -r requirements.txt
```
(if you are using pip for installing packages)
