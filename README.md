# loan-repaid-Keras-API-Deep-Learning-Project

Keras API Project

The Data
We will be using a subset of the LendingClub DataSet obtained from Kaggle: https://www.kaggle.com/wordsforthewise/lending-club

LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California.[3] It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission (SEC), and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.

The Goal
Given historical data on loans given out with information on whether or not the borrower defaulted (charge-off), can we build a model that can predict wether or nor a borrower will pay back their loan? This way in the future when we get a new potential customer we can assess whether or not they are likely to pay back the loan. Keep in mind classification metrics when evaluating the performance of your model!

The "loan_status" column contains our label.

Data Overview can be found in project notebook.

Project Structure:
* Loading Dataset
* EDA
* Data PreProcessing
* Dealing with Missing Data
* Train Test Split
* Normalization of the Data
* Model Creation
* Model Evaluation 
* Prediction of New coustomer 

Model Evaluation:
classification_report
      precision    recall  f1-score   support

           0       0.99      0.43      0.60     15658
           1       0.88      1.00      0.93     63386

    accuracy                           0.89     79044
    
Confusion Matrix
[6773,  8885,]
[45, 63341]



