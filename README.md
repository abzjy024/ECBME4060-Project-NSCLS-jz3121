# Exploring Different Survival Prediction Methods for NSCLC Patients: K Nearest Neighbors and Random Survival Prediction Model

Lung cancer is the most frequent cause of cancer deaths around the world. In order to better predict survival of lung cancer patients , we designed lung cancer survival prediction methods for NSCLC patients based on K nearest neighbors and random survival prediction model. Please refer to the file structure below for more information about the codes. 

File structure 

    --data (containing clinical data, RNA seqence data (including data before and after coexpression) and mutation data)
    
    --coexpression_combination.Rmd (used to do coexpression of RNA sequence data for KNN)
    
    --jg4159_RandomForest (prediction pipeline using Random Forest)
    
    --jz3121_KNN.ipynb (prediction pipeline using KNN)
