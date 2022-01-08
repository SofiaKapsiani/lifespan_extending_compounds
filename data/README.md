**Datasets used for building the random forest models**:

The DrugAge database consists of compounds that “increase” and “do not increase” the lifespan of the nematode *Caenorhabditis elegans* [1]. The entries of the DrugAge database (built 3) were used for building the random forest classifiers. After preprocessing described in [2],  a predictive dataset of 1,430 compounds with 304 positive (increase) and 1126 negative (do not increase lifespan) entries was used. 

- df_descriptors.csv = 2D and 3D chemical descriptors calculated using the MOE software  (https://www.chemcomp.com/Products.htm) 
- df_smiles.csv = canonical SMILES standardised using the Standardiser tool developed by Francis Atkinson (https://github.com/flatkinson/standardiser)

[1] Barardo, D. et al. The DrugAge database of aging-related drugs. *Aging Cell* **16**, 594–597 (2017).
[2] Kapsiani, S. & Howlin, B. J. Random forest classification for predicting lifespan-extending chemical compounds. *Sci. Rep.* **11**, 13812 (2021).
