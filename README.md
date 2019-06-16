# Grab A.I for SEA Challenge 2019 (Safety)

# Pre-requisites to run the codes

pandas, sklearn, CatBoost

# Instructions to run the codes :

1) Specify the location of folder containing training labels in line 26
   
   i.e : label ='[folder location]/part-00000-e9445087-aa0a-433b-a7f6-7f4c19d78ad6-c000.csv'
   
2) Specify the name and location of folder containing holdout set labels in line 31
  
   i.e: holdout_labels ='[folder location]/[name of holdout set labels].csv'
   
3) Specify the location of folder containing ALL data sets (train sets and hold out sets) in line 41
  
   i.e: all_files = glob.glob('[folder location]/*.csv')
   
4) Run the kernel. Final ROC Score of hold out set will be shown at the end of the run.
   
   
