# Data 
### Data Source - https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data

This project utilizes data from the Behavioral Risk Factor Surveillance System (BRFSS), a comprehensive health-related telephone survey conducted annually by the CDC since 1984. The dataset used in this project is from the 2015 survey, which includes responses from 441,455 individuals across 330 features.

The repository contains three CSV files derived from the original BRFSS 2015 dataset:

1. **diabetes_012_health_indicators_BRFSS2015.csv**
   - 253,680 survey responses
   - 21 feature variables
   - Target variable: Diabetes_012 (3 classes)
     - 0: No diabetes or only during pregnancy
     - 1: Prediabetes
     - 2: Diabetes
   - Note: This dataset has class imbalance

2. **diabetes_binary_5050split_health_indicators_BRFSS2015.csv**
   - 70,692 survey responses
   - 21 feature variables
   - Target variable: Diabetes_binary (2 classes)
     - 0: No diabetes
     - 1: Prediabetes or diabetes
   - Balanced dataset with a 50-50 split between classes

3. **diabetes_binary_health_indicators_BRFSS2015.csv**
   - 253,680 survey responses
   - 21 feature variables
   - Target variable: Diabetes_binary (2 classes)
     - 0: No diabetes
     - 1: Prediabetes or diabetes
   - Note: This dataset is not balanced
