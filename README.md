# COVID19_impact_MRN_project
The project aim was to analyse the LTE mobile radio network behaviour before and after the outbreak of the COVID-19 disease, in the metropolitan area of Milan, hence studying the traffic related to the months of January, February and March of 2020: considering the period before the 16th of February as a “Covid free” observation period, and full lockdown starting from the 9th of March. 
The chosen approach has the following structure:  
 - Retrieving the geographical positions of the various antennas from the “Coordinates_MILANO.csv” file. 
 - Checking and organizing the original given data for further processing. 
 - Analysing the behaviour in the month of January, in terms of designated Key Parameters Indicators, to obtain median weekly signatures of the traffic (that would later be useful to discriminate the type of area), and computing the calculation of the median for the periods of February and March as well. 
 - Clustering through the KMeans Classifier in an unsupervised Machine Learning environment, using January as reference. 
 - Focusing on a limited number of eNodeBs, selected from the KMeans clusters, we compared the different trends found in the three months taken into consideration, highlighting what happened because of the outbreak of the disease.  
 - Verifying the correctness and coherence of our results with other general information.

Note: the biggest files were uploaded in this repository as ".zip", and can only be visible raw.
