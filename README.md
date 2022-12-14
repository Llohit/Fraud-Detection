# Fraud-Detection
ML Project

It's A Fruad ..... (https://www.kaggle.com/competitions/its-a-fraud/)

In this competition we are predicting whether an online transaction is fraudulent or not

Transaction Features:

TransactionDT: Timedelta from a given reference datetime (not an actual timestamp), but the time difference in seconds from a certain time.<br>
TransactionAMT: Transaction payment amount in USD, the decimal part is worth paying attention to.<br>
ProductCD: Product code, the product for each transaction. It may not necessarily be an actual product but may also refer to a service.<br>
card1-card6: Payment card information, such as card type, card category, issue bank, country, etc.<br>
addr1-addr2: Address, billing region and billing country<br>
dist: Distances between (not limited) billing address, mailing address, zip code, IP address, phone area, etc.<br>
P_ and (R__) emaildomain: Purchaser and recipient email domain, some transactions do not require the recipient, and the corresponding Remaildomain is empty<br>
C1-C14: Counting, such as how many addresses are found to be associated with the payment card, etc.<br>
D1-D15: Timedelta, such as days between previous transaction, etc.<br>
M1-M9: Match, such as names on card and address, etc.<br>
Vxxx: Vesta engineered rich features, including ranking, counting, and other entity relations. Some V features are missing in different proportions.<br>
Identity Features:

id_01-id_11: Numerical features for identity, which is collected by Vesta and security partners such as device rating, ip_domain rating, proxy rating, etc. Also it recorded behavioral fingerprint like account login times/failed to login times, how long an account stayed on the page, etc.<br>
DeviceType, DeviceInfo and id_12-id_38: Categorical Features<br>

Step1: Preprocessing(Handling categorical features,Handling Null values,Outlier removal)<br>
Step2: EDA<br>
Step3: Training model(Logistic Regression,Random Forest,XGBoost,KNN,....)<br>
Step4: Hyperparameter Tuning(Using Randomized Grid Search)<br>
Step5: Try Multilayer Neural Network<br>

Results :

![image](https://user-images.githubusercontent.com/51969609/207069383-dd85019a-9417-4279-9db2-0559c15c5760.png)
