# Context

The advance of technology gives us all access to conveniences as never seen before. Today it is possible to order anything using cell phone applications. From a simple meal, shopping at the supermarket, or even buying electronic devices have become commonplace tasks - with just one click, without leaving home. 

When we look at the Brazilian market, 7 out of 10 transactions are made by digital means. Those made through smartphones already exceed R$ 16 billion transacted in just one year. And this number can be even higher: according to a survey conducted by the company CupomValido, Brazil is the country that should have the biggest growth in e-commerce, growing twice as much as the world average for the segment.

Credit card is the preferred payment method for purchases in digital channels, representing about 60% of the total transacted. The convenience for many brings complications for the companies responsible for ensuring the security of transactions - in the first quarter of 2022 alone there was a **637%** growth in the number of frauds involving credit cards worldwide. 

The types of fraud are many, however the most common can be classified into 3 categories:

* **Effective fraud**: A purchase is made and when it is time to make the payment the fraudster uses other people's stolen card details. 
* Friendly fraud: When a purchase is made by a person close to the card owner, usually a relative. Since the person does not recognize the purchase, a chargeback request is made.
* Auto Fraud: A card owner makes an online purchase, but they receives the product and contests the value of the purchase as if they did it.

Friendly fraud and self-fraud are by nature difficult to prevent.  However, there are some techniques to prevent *effective fraud* for situations when card data is stolen and misused. Automatic analysis systems verify card owner information, their purchase history, and other information in real time in an attempt to reduce financial impacts for credit card companies. One approach for creating an anti-fraud system is to use machine learning models that can indicate the probability of a given transaction being fraudulent or not.

Our goal in this work is therefore to develop a machine learning model capable of predicting whether a transaction is fraudulent or not. Such a model can have direct application in the industry, preventing future fraud and generating large-scale savings for credit card companies, banks, and payment methods.

### Proposed Solution
* Classification problem
* Metrics 
    * Accuracy
    * Accuracy
    * F1-score
    * ROC curve
* Dataset: 
    * [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* Assumptions: Dataset very unbalanced
* Deliverable: 
    * Anomaly Detection Machine Learning model capable of detecting effective type fraud in credit card transactions
