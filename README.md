# IISc_Project
Useful Codes for Water Resources Engineering Application:

Here I have coded the "abcd" hydrological model in Python. 
The model is widely used for streamflow prediction and watershed modelling. 
It is a lumped model hence all the inputs are spatially averaged data over the watershed. 
The model outputs are also lumped. 
This project primarily focuses on "MAHANADI BASIN" at TIKERPARA GAUGING STATION. 
Rainfall and Temperature data are taken from IMD and Streamflow taken is from INDIA WRIS.
PET is calculated by Thornweite Formula using temperature data and assuming dayhours as 12 hr.
For model calibration, MSE has been used as the minimizing function with optimizing technique as SLSQP.
Data is also provided with the code. 




