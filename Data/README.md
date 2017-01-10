# Data Section

This section contains a record of data used for the development of the model. Note that for large datasets, Git may 
not be able to store all data due to size limitations.

### Raw
The Raw sub-directory contains the raw data assets before any manipulation of the data has been performed.

### Processed
Processed data has been manipulated through the code contained in the /Code/DataPrep directory and is prepared for modeling
activities.

### Model
Model data contains the specific records used to train models in the /Code/Model/ExperimentN directories. The data should be 
stored in the train/test split state if possible, to ensure identical splits in future model runs.
