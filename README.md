### Cancer Drug Response Prediction by Machine_Learning using Gene Expresion and Copy Number Variation Data

*This repo contains my scripts for the Capstone Project in COMPGEN 2022. 

*Briefly, I used GDSC gene expression and copy number variation datasets for 420 different cancer lines and also
the drug response data of each cancer cell line for 11 different drugs. 

*Then, I generated machine learning models that explain the relationships between gene expressiıon and CNV 
profiles and drug responses of each cell line using Random Forest, kNN and ELastic Net algorithms. 

*I evaluated the generated models on another test dataset: gCSI gene expression and CNV data for each drug.

*I decided the best performing models for each drug for each data type (CNV and gene expression) based on
RMSE values and used only these models to predict the drug response profiles of an holdout dataset from gCSI 
gene expression and CMV data.
