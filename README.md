# Bank-Marketing-Campaign-Classification-Model
**Outline**

   >> Business Problem Understanding
   
   >> Data Understanding & Analysis
   
   >> Data Preprocessing
   
   >> Modeling
   
   >> Conclusion and Recommendation

**Business UNderstanding**
One financial product that is well-known to the public is term deposits. The term deposit mechanism is that a customer deposits a sum of money at a bank or a financial institution, and the money can only be withdrawn after a certain period of time. This scheme will allow banks to invest in higher-yield financial products to generate profits. The more customers make deposits, the more the bank will be able to increase its investment and profits. But in return,  customers receive fixed interest based on their deposited amount. **One effective strategy to attract customers to subscribe to a term deposit is through marketing campaigns.**

**GOALS**

The bank aims to identify their customers that have higher chance to subscribe for a term deposit and focus marketing efforts on such clients. The bank wants to have the ability to predict which customers are likely to deposit and conduct marketing campaign to those who genuinely want to subscribe a term deposit. The bank also wants to identify the most important features in subscribing deposits. This way, in the future, the bank can focus on those features. Customers are divided into two targets.
 
Targets :  
*   0 : customer will not subscribe a term deposit
    
*   1 : customer will subscribed a term deposit

**We will build a classification model to help the bank predict whether a customer will subscribe to a term deposit or not.**

METRIC EVALUTAION

We will use confusion matrix for evaluating the performance of our classification model. A good model is one which has high TP and TN rates, while low FP and FN rates. In our case, we want to conduct a marketing campaign accurately for customers who will subscribe a term deposit and keep maintaining a good relationship with all customers. **We will use F1 score metrics for the classification evaluation**. F1 score is types of classification metrics that helpful when we want to consider both false positives and false negatives.
