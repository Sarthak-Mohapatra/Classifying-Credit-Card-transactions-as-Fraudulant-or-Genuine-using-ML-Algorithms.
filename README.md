# Credit Card Fraud Detection.

In today's world, the CARDs industry has been one of the major revenue earning business in the Banking and the Finance industry. It has also been the most favorable payment menthod among customers becuase of the ease in carrying it and at the same time being super efficient in terms of transaction completion time and transaction approval rate. Almost every bank issuing a credit card assures around 98 to 99 percent of transaction approval rate. Because of these factors, the customers are encouraged and prefer to use credit cards in the first place. 

But, in the recent times, one of the major issue that the financial services industry is facing is around Fraud/scams. As stated in Romexsoft's "The Ultimate Guide To Credit Card Fraud Detection in Banking" site, "On a global scale, credit card processing fraud has hit $32.320 trillion in total, with $21.84 billion lost in the US only."

So, it is very important for the Banking and the Finance industry to take proactive measures in identifying Fraudulant Credit Card transactions as it not only affects the banks revenue, but also impacts the financial stability of it's customers.

In this project, I am analysing a large data set on Credit Card data and with use of various Machine Learning algorithms, build the best classification model to classify each transaction as Fradulent or Genuine.

## Table of Contents
- General Info
- Variable Description
- Technologies and Methods
- Status
- Contact

## General Info
The data set was referenced from Kaggle's Data set repository. It contains transactional details made using credit cards by customers in the European Union.The transactions recorded in the dataset occurred in two days. There are a total of 492 frauds (positive class) out of 284,807 transactions. It's an unbalanced data set as the positive class records (Frauds) account for only 0.172% of all transactions.

For the purpose of confidentitality, Kaggle has provided the data set after transforming it by applying Principal Component Analysis. Apart from the Time and Amount field, all the variables and back ground feautures are transformed using PCA. Hence, we cannot use the Credit Cards domain knowledge for providing more meaningful insights. 

## Variable Description
The dataset contains the following variables:
- Time - Number of seconds ellapsed between the current and the first transaction.
- V1 through V28 - Freatures transformed using PCA.
- Amount - The total amount for which the transaction was being done
- Class - A categorical variable which can take values 0 or 1. (0 -> Not Fraud and 1 -> Fraud)

## Technologies and Methods
- R-Studios
- Microsoft Excel (XML)
- Logistic Regression
- K Nearest Neighbour

I am currently building model using Decision Trees and Random Forest methods and checking the accuracy and effectiveness of models.

## Status
Project is: *in progress*

## Contact
If you loved what you read here and feel like we can collaborate to produce some exciting stuff, or if you just want to shoot a question, please feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sarthakmohapatra1990/).
