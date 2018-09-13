# Credit Card Fraud Detection

## Problem Statement
Credit card frauds are on the rise and it is necessary to recognize these fraudulent credit card transactions in order to prevent the customer so that they are not charged for these fraudulent transactions. Machine learning and AI can help in detecting these fraud transactions.  
Explore different methods to classify credit card data as fraud or not. The objective to identify the fraudulent transactions

## Data set
The data set contains transitions which were processed from various credit cards in the month of September 2013 by the European card holders. The data collected has transactions that occurred over the period of two days. There was a total of approximately 300,000 transactions. 
The dataset is highly imbalanced, the fraudulent transactions amounts only to 0.17% of all the transactions processed.

The dataset contains input variables of numerical type which are transformed using Principal Component Analysis. For the confidentiality issues, the source can not provide the original features or any further information regarding the data. The features V1 to V28 are the principal components which are obtained after doing Principal Component Analysis. All the features have been transformed using this method except "time" and "amount". 

"Time" feature represents the seconds elapsed between the specific transaction and the first transaction.
"Amount" is the second feature which contains the data for the transaction amount. This is very useful for example dependent cost sensitive learning.
"Feature" is the response variable of category type. "1" represents fraud and "0" represents no fraud.

Various parts for the project:
### Exploring the Data
This step involves data exploration.
#### Building the Neural Network
#### Visualizing the Data with t-SNE.
Used tensorflow for building the predictive model. After building the model for visualization and analysis used t-SNE to visualize the dataset in two dimensions

# Theory

# Algorithms
 The project will use neural network for detecting frauds using tensorflow library. 
 
 ## 
 
 # Tools and libraries
 ### Python
 ### Jupyter notebook
 ### Tensorflow
 #### Hyperparameters and Optimizations
 Impletemted adam optimizer.

 #### 
 
# Results


## Acknowledgements
The data in this dataset was collected with the purpose of analyzing the data during a research. It was a collaborative effort of Worldline and the Machine Learning Group of ULB on big data mining and fraud detection. More details about this and past projects can be found at http://mlg.ulb.ac.be/BruFence and http://mlg.ulb.ac.be/ARTML
