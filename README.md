# Shapley-based Explainable Clustering for Prognostics and Health Management
This repo contains an annotated Jupyter Notebook written in Julia code for clustering applications for prognostics and health management (PHM).

## Dependencies
This code runs on <b>Julia 1.8.5</b> with the following packages and versions:

- BSON: 0.3.6
- UMAP: 0.1.9
- OrderedCollections: 1.4.1
- DataFrames: 1.5.0
- ScikitLearn: 0.6.6
- Formatting: 0.4.2
- Gadfly: 1.3.4
- PyCall: 1.95.1
- StatsBase: 0.33.21
- ShapML: 0.3.2
- HDF5: 0.16.13 
- IJulia: 1.24.0
- Flux: 0.13.12
- Plots: 1.38.5
- PlotlyJS: 0.18.10
- ProgressMeter: 1.7.2
- XGBoost: 2.2.4

## Dataset
Please head to https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/ and download the 2021 turbofan engine benchmark under the heading <b>17. Turbofan Engine Degradation Simulation-2</b>. The code expects the .h5 files to be placed in a "Data" folder (not included when cloning this repo).
