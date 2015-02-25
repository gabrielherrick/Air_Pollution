# Air_Pollution

These files are part of programming assignment 1 in the Johns Hopkins Coursera course in R programming within the 
Data Science specialization. 

##Function: pollutantmean
'pollutantmean' calculates the mean of a pollutant (sulfate or nitrate) across a specified list of monitors. 
The function 'pollutantmean' takes three arguments: 'directory', 'pollutant', and 'id'. Given a vector monitor ID numbers, 
'pollutantmean' reads that monitors' particulate matter data from the directory specified in the 'directory' argument and 
returns the mean of the pollutant across all of the monitors, ignoring any missing values coded as NA.

##Function: complete
'complete' reads a directory full of files and reports the number of completely observed cases in each data file.

##Function: corr

'corr' takes a directory of data files and a threshold for complete cases and calculates the correlation between sulfate and nitrate for monitor locations where the number of completely observed cases (on all variables) is greater than the threshold.

