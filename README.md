# Customer-Transaction-Prediction-Classification

## <b>PROBLEM CONTEXT
<b>

- BASED ON GIVEN FEATURE OF DATASET WE NEED TO PREDICT WHICH CUSTOMER MAKE TRANSACTION IN THE FEATURE IRRESPTIVE OF THE AMOUNT OF MONEY TRANSACTED


## <b>DOMAIN ANALYSIS
<b>

- With the problem of identification of the customers who will make a transaction with the bank in future, irrespective of the amount of money transacted previously with the bank, the dataset contain 200000 observation with 202 columns with 200 columns having values for var_1 to var_200, one column for ID code and one column for target
  
- TARGET COLUMN
    - 0 Represent -- CUSTOMER DID NOT DO A TRANSACTION
    - 1 Represent -- CUSTOMER DID DO THE TRANSACTION
 

## <b>IMPORTANT NOTE:
<b>

- IN THIS DATA WE NOT DO ANY DOMAIN ANALYSIS BECAUSE OF WE DONT HAVE ANY FEATURE NAME BECAUSE THE DATA IS CONTAIN PRIVATE INFORMATION OF CUSTOMER DETAILS OF BANK


### <b>TYPES OF MACHINE LEARNING PROBLEM.
- <b>It is a binary classification problem, where given the above set of features, we need to predict if a given patient has liver disease or not.<br>
### <b>LIST OF ALGORITHMS USES FOR CLASSIFICATION
<b>

- Logistic Regression
- Artificial Neural Network [MLP Classifier]
- XGB Classifier


# <b>TASK 1
## <b>PREPARE A COMPLETE DATA ANALYSIS REPORT ON THE GIVEN DATA.

# <b>TASK 2
## <b>CREATE A PREDICTIVE MODEL WITH IMPLEMENTATION OF DIFFERENT CLASSIFIERS


### <b>NOTE
<b>
    
- FROM ABOVE XGBOOST AND MLP CLASSIFIER MODEL I WAS ABOUT TO USE HYPERPARAMETER TUNNING BUT THE DATA IS VERY HUGE AND IT TAKES MORE TIME TO FIT THE DATA ALSO IM TRYING ON GOOGLE COLAB AS WELL BUT NOT SOLVE THE TIMINING PROBLEM THAT WHY I'M REMOVE THE ALL HYPERPARAMETER TUNNING.



### <b>SUMMARY
<b>

  
| **Model**            | **Training Score (%)** | **Testing Score (%)** | **F1 Score (%)** | **Remarks**                                                                    |
| -------------------- | ---------------------- | --------------------- | ---------------- | ------------------------------------------------------------------------------ |
| Logistic Regression  | 83.56                  | 83.54                 | 83.69            | Performance remains poor even after applying Bagging                           |
| ANN (MLP Classifier) | 93.87                  | 90.47                 | 90.58            | Selected model; works well on both training and testing; tuned with `max_iter` |
| XGBoost Classifier   | 93.77                  | 90.60                 | 90.67            | Strong performance, comparable to ANN                                          |
