# ChrX_prediXcan
Predict the expression of X chromosome genes with the elastic net regression model. Models can be used for TWAS with the PrediXcan pipeline: https://github.com/hakyimlab/PredictDB-Tutorial. 

## Citation
Zhang X, Gomez L, Below JE, Naj AC, Martin ER, Kunkle BW, Bush WS. An X Chromosome Transcriptome Wide Association Study Implicates ARMCX6 in Alzheimer's Disease. J Alzheimers Dis. 2024 Mar 14. doi: 10.3233/JAD-231075. Epub ahead of print. PMID: 38489177.

## Notes
The models were trained with GTEx whole blood and brain cortex data. 

We implemented nested cross-validation to train the elastic net regression models with a mixing parameter of 0.5 (50% ridge penalty and 50% LASSO penalty). 

We recommend using the sex-stratified models for transcriptome-wide association studies (TWAS).
