# SOLUBILITY_CHEMPROP
INTRODUCTION

Predticting solubility my running machine learning models with the help of chemprop
It is based on the workflow provided by HASTEN, which helps in boosting virtual screening workflows. 

DESCRIPTION:
1% of the satais selected from the entire dataset to build the model and precdicted on the rest. Another 1% is selected from the predicted dataset and added to the initial dataset and again used to build the model. This is done for n number of iteration till desired performance is achieved. 

DATASET: collection of 7 cured datasets (AqSOL, AQUA, ESOL, CHEMBL, KINECT, OCHEM, PHYS) retrieved from paper on "Boosting the predictive performance with aqueous solubility dataset curation"


REFERNCES: 
 Meng, J., Chen, P., Wahib, M. et al. Boosting the predictive performance with aqueous solubility dataset curation. Sci Data 9, 71 (2022). https://doi.org/10.1038/s41597-022-01154-3
