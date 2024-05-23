running time can be beetween 10 min and 30 mins depending on the number of itirations for each model 
LIGHTGBM has an AUC (area under curve) of 75% without any optimization - you could optimize the model by using grid search, random ssearch and specifiying a good #folds , also it can be done by tuining the parameters manually 
Nueral Network has around 50% without any optimizaton 

- Change the input path of the dataset before running the script / please mind the encoding of the csv files before running the script
- file 1 has lightgbm model
- file 2 has the lightgbm and nueral network
- also included a schema picture to explain the depth of each aggraigation in the datasets
- both models are trained on 2.7gb of Data / you can do more by going cloud based model or deeploying it on cloud
- Pandas is used in handling the featuree engineering and manipulation
- Polar can be used but it's kinda complex and new "TO ME", it wont achieve better results but it will cut the time of runnign into half !


*Albara.sasbbagh@gmail.com
  
