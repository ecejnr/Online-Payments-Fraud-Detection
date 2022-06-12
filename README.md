# Online Payments Fraud Detection with Machine Learning Algorithms
 Online Payments Fraud Detection 

 What is fraud detection?
According to the definition provided by the Cambridge Dictionary, fraud is the “crime of getting money by deceiving people.” Fraud has existed in one form or another for many centuries. Ever since people started to exchange goods and services, there has been a risk of one party scamming another and third parties scamming both sellers and buyers. 

Fraud undergoes regular changes and transformations. It’s gained new forms with the e-commerce expansion. Fraudsters take full advantage of every weak spot detected in online banking, online insurance, e-shopping, and other niches. Fraud has become a major issue for e-commerce and banking retailers globally. 

Detecting, preventing, and fighting fraud are among the primary concerns in the modern-day world. One of the most effective ways of managing attacks and risks is by using machine learning algorithms for fraud detection.

Machine learning is useful in so many ways. It’s been widely used for email spam detection, providing customer-focused recommendations on e-commerce platforms, and much more. The possibility to work with large data volumes makes machine learning one of the best choices for building fraud detection technologies. Thanks to the constant advancements in machine learning, e-commerce, and online banking sectors can take significant advantages in preventing cyber-crime and keeping sensitive data safe. 

Why use machine learning (ML) algorithms for fraud detection?
Machine learning (ML) is the science of creating and applying algorithms capable of analyzing and learning from past events. ML is the perfect use case in fraud detection and prevention. Machine learning is capable of detecting fraud from legitimate actions.

The idea behind machine learning usage for fraud detection is that fraudulent transactions include elements that legitimate ones lack. Unlike humans, ML can fight big volumes of fraud way faster and in a timely manner. Machine learning can process a raft of information faster and better than most experienced analysts would do. ML algorithms can spot the cases of fraudulent and unhealthy behavior patterns 24/7/365, remember them forever, and prevent further use cases.

STEPS TAKEN TO COMPLETE THIS PROJECT:
- importing the python library packages
- Import the data and load
- performed EDA a much as feasible
- found out the types of fraudulent transaction types out of all the transaction modes.
- figured out the fraud in the selected types
- figured the minimum and maximum transaction from Transfer and cash out transaction mode when it is set to be Fraud
- defined a dataset containing only transfer type of transactions
- created dependent set X
- removed unwanted columns
- labeled encoding for the transaction type (to change categorical data to numerical)
- created independent set Y and droping it from dependent set Y
- split the dataset into train and tests
- imported important metrics used to evaluate the models
- performed standard scaling on the data for better fit
- modelling using Random Forest classifier, Logistic Regression, Decision Tree Classifier and K nearest Neighbor.
- performed model evaluation for every model imported.