running time can be beetween 10 min and 30 mins depending on the number of itirations for each model 
LIGHTGBM has an AUC (area under curve) of 75% without any optimization - you could optimize the model by using grid search, random ssearch and specifiying a good #folds , also it can be done by tuining the parameters manually 
Nueral Network has around 50% without any optimizaton 

- Download the Data from kaggle via the API or Manually via the download button
- Exclude the parquet files , they're duplicates from the csvs 
- Change the input path of the dataset before running the script / please mind the encoding of the csv files before running the script
- file 1 has lightgbm model
- file 2 has the lightgbm and nueral network
- also included a schema picture to explain the depth of each aggraigation in the datasets and how I Handeled the Type Casting in each column 
- both models are trained on 2.7gb of Data / you can do more by going cloud based model or deeploying it on cloud
- Pandas is used in handling the featuree engineering and manipulation
- Polar can be used but it's kinda complex and new "TO ME", it wont achieve better results but it will cut the time of runnign into half !
- Aggregating depth 1 and depth 2 into thier propar methods then merged the tables into each other "This been done in Train and Test Data"
- The Train Data is : (915995, 48) 
- The Valid Data is : (305332, 48)
- The Test Data is : (305332, 48)
- Totalling more than 1 Million Rows (Can't be opened in excel if you append them)
- Please note that when the model is deployed the label classified is the "Probability of the [Client to default on their loans] " and it's not a 1 or 0
- There's a depth guide of LIGHTGBM model in the IPYNB file (IF needed)
- If you needd better idea on the model , plot the AUC vs Itirations to see if the model can achieve betetr AUC when adjusting the Early Stopping functon 

*Albara.sasbbagh@gmail.com
  
