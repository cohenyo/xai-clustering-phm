# Shapley-based Explainable Clustering for Prognostics and Health Management
This repo contains an annotated Jupyter Notebook written in Julia code for clustering applications for prognostics and health management (PHM). The tutorial notebook encompasses the creation of a predictive model as well as utilizing the proposed XAI clustering framework to visualize and describe the model's behavior. This code accompanies our arXiv paper, "Shapley-Explainable Clustering Analysis for Fault Diagnosis and Prognosis". If you find this repo or the paper helpful, please use this citation in your research:

J. Cohen, X. Huan, and J. Ni (2023). Shapley-Explainable Clustering Analysis for Fault Diagnosis and Prognosis, [arXiv:2303.14581](https://arxiv.org/abs/2303.14581).

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
Please head to [NASA's PCoE repository](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/) and download the 2021 turbofan engine benchmark under the heading <b>17. Turbofan Engine Degradation Simulation-2</b>. The code expects the .h5 files to be placed in a "Data" folder (not included when cloning this repo). When using this dataset, please use the following citation:

M. Chao, C.Kulkarni, K. Goebel and O. Fink (2021). “Aircraft Engine Run-to-Failure Dataset under real flight conditions”, NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA
