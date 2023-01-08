# IDS-in-IoV

## Dataset links

inter-vehicle : https://www.kaggle.com/datasets/devendra416/ddos-datasets

intra-vehicle : https://sites.google.com/a/hksecurity.net/ocslab/Datasets/car-hacking-dataset

download dataset and keep all *.csv files in dataset folder

## Pre-processed Data
create a folder data in working directory inorder to store preprocessed data

## Requirements
pip install "dask[complete]" dask_ml

pip install sklearn

pip install tensorflow

## How to Run Colab Files
upload pre-processed data to drive and run the colab files

## Understanding Code
In confusion matrix 
    - inter files 0-Benign 1-ddos
    - intra files 0-Dos 1-Fuzzy 2-Normal 3-Spoof
