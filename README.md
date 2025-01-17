# Demand-Flexibility-Model
Simulation tool for assessing the techno-feasibility of demand flexibility integration in power system


Google drive link for input data - https://drive.google.com/drive/folders/1YfCc-ZFRKju_qhDR--8nTc3OjctD3QmA

User instructions:
step 1: import required libraries
step 2: read input data and specify input data path
step 3: set flexibility levels in % for each cluster and mode of flexibility (i.e. DF/DR etc)
step 4: set the parameters in tariff calculation module
step 5: set the inconvenience cost in demand optimisation module
step 4: run RE forecasting module (input data: plant wise csv files, weather data files)
step 5: run k-means clustering module (input data: category wise smart meter data files, ex. residential.csv, hospital.csv etc)
step 5: specify number of iterations for iterative algorithm 
step 6: execute the algorithm 
step 7: plot the graphs: simulation results

