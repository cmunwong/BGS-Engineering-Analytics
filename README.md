# BGS Engineering Analytics
### Objective: 
Use the information on used cars previously sold in the "Training_Dataset.csv" file to predict vehicle trim and dealer listing price given the other twenty-six variables provided in the "Test_Dataset.csv" file.

### CSV Datasets: 
- [Training_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Training_Dataset.csv)
- [Test_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Test_Dataset.csv)
- [Prediction_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Prediction_Dataset.csv) (final results)

### Steps:
1. Data Cleaning: *Replace the missing numerial data with the column average and the missing categorial data with "Missing" category.*
2. Data Transformation: *Transform all categorial data into interger.*
3. Data Modeling: *Split the traning dateset in two, one for model training and one for model evaluation.*

   *Build and fit the Machine Learning Models:*
   - *DatasetLasso Regression*
   - *Ridge Regression*
   - *Elastic Net*
   - *Random Forest*
   - *Gradient Boosting Machines*
     
5. Model Evaluation: *Select the best model with the highest R^2 and the lowest MAE.*
6. Data Prediction: *Predict the test dataset using the selected model.*


### Problem Statement
Included in these materials please find two comma separated values (.csv) files: [Training_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Training_Dataset.csv) and [Test_Dataset.csv](https://github.com/cmunwong/BGS-Engineering-Analytics/blob/main/Test_Dataset.csv)

Included in the training dataset is information on used cars previously sold. Each row corresponds to one used car listing. The first column of the data contains a unique identifier for the listing. The next twenty-six columns contain information on parameters relevant to the transaction, with those parameters described in more detail in the appendix attached. Finally, the last two columns of the “Training_dataset.csv” contain information on “Vehicle_Trim” and “Dealer_Listing_Price”, which describe the trim of the vehicle involved in the sale, and the price at which the vehicle was listed by the dealer.

Your challenge is to build one or more models, through whatever means you find most appropriate, capable of predicting vehicle trim and dealer listing price given the other twenty-six variables provided.

### Instructions
1. Model the problem using whatever means you consider best. Your work is expected to be
entirely your own. You may consult any resource or reference of your choosing to aide in solving the problem, but the work must be entirely yours. Please reference any resources you use in the write-up covered in step 5.
2. If you use a software package to assist you, please include ALL of your original source code in its entirety, and submit it to us EXACTLY following the instructions in Steps 5 and 6. Please also include information about which package you used and why in your brief problem write-up.
3. Do not use or add data from any third-party sources, such as internet car estimating tools, to the data provided. At your discretion, some or all of the provided data in “Training_dataset.csv” may be used, omitted or manipulated in any way during modeling, but no additional data may be added from outside sources.
4. Once your model is built, use it to make predictions on EACH of the 1,000 vehicle listings included in the “Test_dataset.csv” file. Your output should be a comma separated values (.csv) file with one-thousand rows and three columns. The first column should be the unique identifier for the listing. The second column should be your predicted value for vehicle trim. The third column should be your predicted value for dealer listing price.
5. Please submit a brief write-up of no more than 500 words describing the approach you selected and why. Please save your response as a PDF if possible. Please copy any source code from Step 2 and paste it as text into an appendix at the end of your write-up.
6. Return your submission to us by replying back to the original email before the date and time specified in that email. Please attach the CSV containing your predictions from Step 4 and the PDF containing your write-up and source code from step 5 to the email. It should contain ONLY two attachments: the CSV from step 4 and the PDF from Step 5. Please don’t resubmit any of our original data back in your reply.

IMPORTANT: You must follow the submittal instructions in Steps 5 and 6 EXACTLY in order for your email not to be prevented from reaching us by the Boeing email firewall. If you do not receive an email acknowledging receipt of your email within two business days of your submittal, please contact us again via email to confirm your materials were received. Thank you!

### Evaluation
Your models will be evaluated on several objective criteria such as overall R-squared and Area Under the Curve (as appropriate). We will also be looking at some qualitative aspects of the code considering the overall approach and style.
