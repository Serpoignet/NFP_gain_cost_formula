# NFP_gain_cost_formula
An interactive python notebook dedicated to calculating a gain metric from following a model's predictions

## Requirements
This code uses interactive python (ipykernel), matplotlib, and numpy to run. An Anaconda environment that can run this code was extracted and provided in env.yml

## Components
### gain_cost_formula.ipynb
The code file in an interactive python notebook gain_cost_formula.ipynb. This file calculates the theoretical monetary gain of following predictions of a ML model for the telecommunication Network Fault Prediction (NFP) problem, compared to without predictions. This theoretical gain is presented in a graph along the axes of common classification ML metrics that are Precision and Recall.

### gain_cost_formula_f1_score.png
gain_cost_formula_f1_score.png is a representation of a common ML classification metric, that considers Precision and Recall equally. It is only provided for the example as a comparison.

### gain_cost_formula_w_sanctions_w_earlyintfailure_w_paper.png
This representation of the theoretical gain includes a dot representing the values of a study of NFP. This was made solely for the use in a related paper. Not all NFP studies were placed on this graph as they were not designed on the same dataset and are therefore not comparable directly.

### Other png files
The other png files are the outputs calculated with the given parameters. They are calculated with and with SLA sanctions, and with and without considering that early interventions might fail. More details are provided in the related paper.

### env.yml
env.yml is the extracted anaconda python environment the code was run on. It is provided for convenience but the exact version are not necessary. (see conda-cheatsheet for reference on how to use)
