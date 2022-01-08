
**Models used for predicting lifespan-extending compounds**:
-	ECFP_1024.ipynb = random forest classifier built with Extended Connectivity Fingerprints (ECFPs) of 1,024-bit length. The fingerprints were generated using the RDKit python module from the standardised canonical SMILES from the df_smiles.csv file (found in the data directory).
-	MD.ipynb = random forest classifier built using 2D and 3D chemical descriptors using the df_descriptors.csv file (found in the data directory). This model achived the highest AUC score from the classifiers built in the “Random forest classification for predicting lifespan-extending chemical compounds” paper (https://doi.org/10.1038/s41598-021-93070-6)) 
