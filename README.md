# Machine Learning Individual Project

## Rank Achieved

![alt text](https://github.com/AshanMSilva/ML-individual-project/blob/main/images/Pump_it_rank.png?raw=true)

## Pre-processing & Feature Engineering

1. Look for missing and false data

      1. There was some Nan values in features such that funder and installer. Therefore used new category called Other to filled tose missing values.
      2. Also there was many false values in features such that 'amount_tsh', 'population', 'gps_height' and 'construction_year', Corrected those false values by replacing those values using median or mean. 
      
2. Plot and look relations between features and labels

      ![alt text](https://github.com/AshanMSilva/ML-individual-project/blob/main/images/plot_data.png?raw=true)
      
      Look for unnecessary data using graphs.
3. Remove unnecessary features
      1. There were some duplicate features in the dataset such that 'quality', 'quantity' and 'payment_type'. Remove those unnecessary features.
      
      ![alt text](https://github.com/AshanMSilva/ML-individual-project/blob/main/images/extraction_type.png?raw=true)
      
      ![alt text](https://github.com/AshanMSilva/ML-individual-project/blob/main/images/water_quality.png?raw=true)
      
      2. In some features more values are missing and remove them.
4. Re-categorized some features with custom categories
      1. There were some features with 'Other' and 'unknown' categories and combined them as one.
      2. Also some features reproduce with custom categories. 
5. Add additional features
      1. Create new feature called 'duration' using 'date_recorded' and 'construction_year'.
      2. using get_dummies() function in pandas create new features using categorized features. (One hot Encoding)
   
6. Normalize data
      1. Factorize data. (Label Encoding)
      2. Normalize data using standard deviation or min-max normalization.
