# GeoLifeCLEF 2023

This repository is related to the GeoLifeCLEF challenge. The details of the challenge, the data, and all other useful information are present on the challenge page: [https://www.kaggle.com/competitions/geolifeclef-2023-lifeclef-2023-x-fgvc10](https://www.kaggle.com/competitions/geolifeclef-2023-lifeclef-2023-x-fgvc10 "GeoLifeClef2023 kaggle page!")

## codes
In this repository you will find dataloaders, sample_data and example to help using the challenge's dataset.
- In ``data/sample_data/`` you will find a small sample of the dataset to try codes and loaders.
- ``example_patch_loading.ipynb`` and ``example_patch_loading.py`` give an example of pytorch dataset creation for CNN tensors taking into account different cases.
- ``example_time_series_loading.ipynb`` and ``example_time_series_loading.py`` give an example of pytorch dataset creation for time series tensors taking into account different cases.

## Environment
 We provide a conda environment containing the needed libraries to use this code.
 ```conda env create -f environment.yml```
 ```conda activate glc23```

 <!-- myspace -->