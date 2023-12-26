# BGS Engineering Analytics
### Objective: 
Use the information on used cars previously sold in the "Training_Dataset.csv" file to predict vehicle trim and dealer listing price given the other twenty-six variables provided in the "Test_Dataset.csv" file.

### Datasets: 
- [Training_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Training_Dataset.csv)
- [Test_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Test_Dataset.csv)
- [Prediction_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Prediction_Dataset.csv) (final results)

### Python code:
- [Prediction.ipynb](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Prediction.ipynb)

### Steps:
1. Data Cleaning: *Replace the missing numerial data with the column average and the missing categorial data with "Missing" category.*
2. Data Transformation: *Transform all categorial data into interger.*
3. Data Modeling: *Split the traning dateset in two, 80% for model training and 20% for model evaluation.*

   *Build and fit the Machine Learning Models:*
   - *DatasetLasso Regression*
   - *Ridge Regression*
   - *Elastic Net*
   - *Random Forest*
   - *Gradient Boosting Machines*
     
5. Model Evaluation: *Select the best model with the highest R^2 and the lowest MAE.*
6. Data Prediction: *Predict the test dataset using the selected model.*
