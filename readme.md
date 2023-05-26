# Identifying Likely-reputable Projects in the ethereum blockchain 

This project applies a machine learning model namely LightGBM to build a model that can identify reputable smart contracts using their transaction history.

> Focuses on Ethereum 

* The reputable projects are gathered from CoinGecko
* Illicit projects/ accounts are provided by the Ethereum community as flagged. 

## Prerequisites

Python is required, I used the [Anaconda](https://www.anaconda.com/download) distribution.
LightGBM can be downloaded from [here](https://lightgbm.readthedocs.io/en/latest/Installation-Guide.html)

Note: The main file is a .ipynb file, thus Jupyter Notebook is required. 

## Model 
The model itself can be found in [/models/final_mode.ipynb](/models/final_model.ipynb)
Note that you need LightGBM, pandas, sci-kit learn to run the file.
A complete list of libraries utilised can be found in Appendix C of the FYP report

## Datasets 
For future use and purposes, I provide the following datasets

* Reputable set of projects [/datasets/reputable_projects.csv](/datasets/reputable_projects.csv)
* Illicit set of accounts [/datasets/illicit_projects.csv](/datasets/illicit_projects.csv)
* Complete accounts [/datasets/complete_projects.csv](/datasets/complete_projects.csv)

## Figures 
Figures are provided in the figures [/figures/](figures/)

## Report 
The Report is provided in the [/fyp_report/](fyp_report/ethereum_reputability_fyp.pdf)


