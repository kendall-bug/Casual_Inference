# Casual_Inference

# **Causal Inference**
When running a causal inference model, typically you are attempting to identify if some sort of treatment or intervention was effective in changing the outcomes of a particular event or phenomenon. For example, in economic policy, you may want to determine if a government program for first-time homebuyers was effective or not at remediating the housing crisis in your community. In medicine, you may want to see if participating in an exercise program caused people to have better health outcomes or not.

In this notebook, I am applying causal inference to the retail indsutry. In the context of retail, your intervention may be a promotion that you're running on a product, and you're attempting to determine if the promotion was effective in driving an increase in sales or not.

**Scenario:** This dataset was adopted from Kaggle's Store Item Demand Forecasting Challenge dataset (https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data?select=train.csv).  

***In Store 1, store managers noticed that Item 1 isn't selling as much as it used to. On May 31, 2015, the store's leadership decided to run a one-day promotion on the item to see if that would attract more customers to buy the product.***

**Outcome:** By comparing patterns observed during Store 1's promotion to trends observed in stores that were not effected by the promotion, we are able to identify if there is a causal relationship between the promotion and sales. In other words: can we attribute the fluctuations in sales of Item 1 to the promotion? Or are those fluctuations purely by chance?
