# ChrX_prediXan
Predict the expression of X chromosome genes with the elastic net regression model. Models can be used for TWAS with the [PrediXcan pipeline]([url](https://github.com/hakyimlab/PredictDB-Tutorial.git)).

## Citation
Zhang, X. et al. Predicting genetically regulated gene expression on the X chromosome. http://biorxiv.org/lookup/doi/10.1101/2023.06.06.543877 (2023) doi:10.1101/2023.06.06.543877.

## Notes
The models were trained with GTEx whole blood and brain cortex data. 

We implemented nested cross-validation to train the elastic net regression models with a mixing parameter of 0.5 (50% ridge penalty and 50% LASSO penalty). 

We recommend using the sex-stratified models for transcriptome-wide association studies (TWAS).
