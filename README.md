# Preliminary Experiments for DuckDQ

## Install
1. Install Docker
2. Open Shell
3. git clone https://github.com/tdoehmen/duckdq-experiments.git
4. cd duckdq-experiments

## Run Evaluation Script
In Windows PowerShell: > .\eval_script.ps1

In Linux/OSX shell: > .\eval_script.sh

(evaluation script can take up to 1h, depending on the system)

## Run Interactive Evaluation (Jupyter Notebook-based)
In Windows PowerShell: > .\eval_interactive.ps1

In Linux/OSX shell: > .\eval_interactive.sh

For Experiments in Group A: Open Chrome/Firefox/Safari, go to: http://localhost:8890/notebooks/work/eval_a.ipynb

For Experiments in Group B: Open Chrome/Firefox/Safari, go to: http://localhost:8891/notebooks/work/eval_b.ipynb

(Because the experiments require different environment, they are split up into two groups.)

## Dataset

A ~3M row / 10 column subset from a hotel recommendations challenge on Kaggle ([https://www.kaggle.com/c/expedia-hotel-recommendations/data](https://www.kaggle.com/c/expedia-hotel-recommendations/data))
