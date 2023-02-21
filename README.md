# ABCD Sex-Specific Clinical Predictions



This repository contains the Jupyter Notebook based implementation of the work described in: 
Dhamala, E., Ooi, L.Q.R., Chen, J., Ricard, J.A., Berkeley, E., Chopra, S., Qu, Y., Lawhead, C., Yeo, B.T. and Holmes, A., 2022. Brain-based predictions of psychiatric illness-linked behaviors across the sexes. bioRxiv, pp.2022-12.

Keywords: prediction psychiatry, neuroimaging, functional connectivity, brain-based predictions, sex differences, transdiagnostic

This implementation was used to evaluate the generalizability of sex-specific functional connectivity-based predictions of problematic behaviors across sexes and across behaviors in the ABCD data. 

Below are descriptions of each Jupyter Notebook: 
01_clinpreds_trainmodels.ipynb: optimise and train models to predict behavioral scores based on FC data
02_clinpreds_testmodels.ipynb: evaluate trained models across behaviors and across sexes
03_clinpreds_nullmodels.ipynb: generate null models using optimised regularization parameters
04_clinpreds_evaluatemodels.ipynb: evaluate whether true models perform better than null models
05_clinpreds_haufetransform.ipynb: compute haufe-transformed feature weights 
