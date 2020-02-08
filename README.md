# House-Price-Prediction
Structure:
Introduction
Data Loading
EDA - Univariate
EDA - Bivariate
Data Preprocessing
Model Building with Dataset-1
Hypertuning Dataset-1
Summary - Dataset-1
Model Building with Dataset-2
Hypertuning Dataset-2
Summary - Dataset -2
Conclusion
Pickle file creation

Note: 
Dataset - 1 = 22 features
['price', 'room_bed', 'room_bath', 'living_measure', 'lot_measure', 'ceil', 'coast', 'sight', 'condition', 'quality', 'ceil_measure', 'basement', 'yr_built', 'living_measure15', 'lot_measure15', 'furnished', 'total_area', 'month_year', 'City', 'has_basement', 'HouseLandRatio', 'has_renovated']

Dataset - 2 = 31 features (important features after imputing dummy and analyzing different models) 
['price', 'room_bed', 'room_bath', 'living_measure', 'lot_measure', 'ceil', 'sight', 'condition', 'ceil_measure', 'basement', 'yr_built', 'yr_renovated', 'zipcode', 'lat', 'long', 'living_measure15', 'lot_measure15', 'total_area', 'coast_1', 'quality_3', 'quality_4', 'quality_5', 'quality_6', 'quality_7', 'quality_8', 'quality_9', 'quality_10', 'quality_11', 'quality_12', 'quality_13', 'furnished_1'

Prerequisites for the running the file:
Below are 2 files needed to be added to you current working directory.

 1. Need to add file USA ZipCodes_1.xlsx to current working directory to access this data 
 2. Add the folder WA to your current working directory
 3. Install below 2 libraries
    conda install -c conda-forge/label/cf201901 geopandas 
    conda install -c conda-forge/label/cf201901 shapely 

This Jupyter Notebook is done as part of PGPML Great Learning Programme for Capstone Project. Let's first, define the problem, objective of this excercise.

We have the problem statment well defined in the given document which is as follows
