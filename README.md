# ImperialWRR

WRR.Zip contains full input data and modelling scripts to support WRR submission 'Localized Hydrological Drought Early Warning using In-situ Groundwater Sensors'.

'WRR_Data_Extraction' contains input data and processing of these for model input.

'WRR_Modelling_Methods' contains two folders. 'Groundwater Model & Calibration' provides the code for the modified AquiMod, formatted for input in to an automated calibration procedure (run time approx. 5 minutes with 10,000 runs). The 'Plotting Files' folder contains the code converting the groundwater levels from the automated calibration procedure to plots seen in the paper.

These scripts require use of the data and functions within the 'data_and_functions' folder, which may require careful directory management and minor edits to the code to ensure the scripts can communicate.
