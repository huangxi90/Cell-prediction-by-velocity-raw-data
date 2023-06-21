# Cell-prediction-by-velocity-raw-data
This repository contains the raw data for the paper "Predicting the number of printed cells during inkjet-based bioprinting process based on droplet velocity profile using machine learning approaches" at https://doi.org/10.1007/s10845-023-02167-4

train-test.csv contains the data of cell count, concentration of cells, and velocity of the printed droplet at 0.7, 1.0, 1.5, 2.0, 2.5, and 3.0 mm from the nozzles.

rfr-model.sav and etr-model.sav is the trained model file using random forest regression and extra tree regression respectively, using the raw data from train-test.csv.

validation-1.0-2.0.csv contains the data for validation set of 10 droplets per batch (The batch is consecutively printed. 
The droplet velocity of droplet N in a batch for 1.0 mm and 2.0 mm from the nozzle is under the label (2N-1) and (2N) respectively.
