# Customer Segmentation
Customer segmentation is the strategic process of identifying and grouping a company's existing and potential customers into distinct subsets based on meaningful and actionable shared characteristics. These characteristics can include demographics, behavior, psychographics, and geographic location, among others. The goal of customer segmentation is to tailor marketing, sales, and service efforts to meet the specific needs and preferences of each group, ultimately leading to increased customer satisfaction, loyalty, and profitability.

## Why is Customer Segmentation Important?

- **Personalized Marketing**: Enables the creation of targeted and relevant marketing campaigns.
- **Improved Customer Experience**: Delivers tailored experiences that resonate with specific customer needs.
- **Increased Customer Loyalty**: Makes customers feel understood and valued, fostering stronger relationships.
- **Higher Conversion Rates**: Targeted offers are more likely to lead to sales.
- **Optimized Resource Allocation**: Focuses marketing and sales efforts on the most promising customer groups.
- **Better Product Development**: Provides insights into customer needs and preferences, informing product innovation.

# About this project
____

This notebook aims at analyzing the content of an E-commerce database that lists purchases made by $\sim$4000 customers over a period of one year (from 2010/12/01 to 2011/12/09). Based on this analysis, we'll be able to anticipate the purchases that will be made by a new customer, during the following year and this, from its first purchase. <br>

Dataset link:- https://www.kaggle.com/datasets/carrie1/ecommerce-data


___
**1. Data Preparation**

**2. Exploring the content of variables**

   - 2.1 Countries
   - 2.2 Customers and products
       * 2.2.1 Cancelling orders
       * 2.2.2 StockCode
       * 2.2.3 Basket price

**3. Insight on product categories**

   - 3.1 Product description 
   - 3.2 Defining product categories 
       * 3.2.1 Data encoding
       * 3.2.2 Clusters of products
       * 3.2.3 Characterizing the content of clusters
   
**4. Customer categories**

   - 4.1 Formating data
       * 4.1.1 Grouping products 
       * 4.1.2 Time spliting of the dataset
       * 4.1.3 Grouping orders 
   - 4.2 Creating customer categories
       * 4.2.1 Data enconding
       * 4.2.2 Creating categories

**5. Classifying customers**

   - 5.1 Support Vector Machine Classifier (SVC)
       * 5.1.1 Confusion matrix
       * 5.1.2 Leraning curves 
   - 5.2 Logistic regression 
   - 5.3 k-Nearest Neighbors
   - 5.4 Decision Tree
   - 5.5 Random Forest
   - 5.6 AdaBoost
   - 5.7 Gradient Boosting Classifier
   - 5.8 Let's vote !
   
**6. Testing the predictions**

**7. Conclusion**


# Conclusion

The work presented herein details a comprehensive methodology for analyzing and predicting customer behavior within an e-commerce environment. Commencing with the classification of products into five key categories, we proceeded to segment our customer base into eleven distinct profiles based on their purchasing habits over a ten-month interval, considering product preferences, visit frequency, and spending patterns. We then trained and evaluated several classifiers to predict these customer segments using only the data from their initial purchase, specifically the mean basket value and the percentage of expenditure across the five product categories. Our evaluation, conducted on the subsequent two months of data, yielded a classification accuracy of 75%, indicating a reasonably effective model. However, we acknowledge a significant potential bias arising from the seasonality of purchases. The customer segments defined over a ten-month period may not entirely reflect purchasing behaviors during different periods, such as peak holiday seasons. To mitigate this limitation, future investigations should focus on acquiring and analyzing data spanning a longer duration to capture and model these seasonal effects, thereby leading to a more accurate and reliable predictive framework for customer behavior.
