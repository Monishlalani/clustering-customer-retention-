# clustering-customer-retention-

## Tools and Technology used:
[![MATPLOTLIB](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge)](https://img.shields.io/badge/-MATPLOTLIB-007aa6?style=for-the-badge) [![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) [![Jupyter](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge)](https://img.shields.io/badge/-Jupyter-f5841f?style=for-the-badge) [![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white) [![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white) <a href="https://seaborn.pydata.org/" rel="nofollow"><img alt="SEABORN" src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-SEABORN-f5841f?style=for-the-badge" style="max-width: 100%;"/></a>
<a href="https://www.microsoft.com/en-in/microsoft-365/excel" rel="nofollow"><img alt="Excel" src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" data-canonical-src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" style="max-width: 100%;"/></a><a href="https://www.geeksforgeeks.org/clustering-in-machine-learning/" rel="nofollow"><img alt="Clustering" src="https://img.shields.io/badge/-Clustering-e4a663?style=for-the-badge" data-canonical-src="https://img.shields.io/badge/-Clustering-e4a663?style=for-the-badge" style="max-width: 100%;"/></a>


## Business Objective
Amazon Product Review Analysis
- Grouping on the basis of Review id to make the type of customer based on there sentiment score

- Customer retention refers to the ability of a business to keep its customers over time. 
- It is the process of ensuring that existing customers continue to do business with a company, rather than switching to a competitor. 
- Sentiment analysis can help businesses understand the factors that drive customer loyalty.
- By understanding customer sentiment, businesses can take steps to address any issues or concerns that may be causing dissatisfaction and leading to churn.


There are several strategies that companies can use to improve customer retention: 
 
1.	Providing high-quality products or services that meet or exceed customer expectations. 
2.	Building strong relationships with customers through excellent customer service and effective communication. 
3.	Offering personalized experiences and tailored promotions to meet the specific needs of individual customers. 
4.	Continuously improving products and services based on customer feedback. 
5.	Creating loyalty programs that reward customers for repeat business. 
6.	Providing transparency and trustworthiness to build a strong brand reputation. 
7.	Being proactive in addressing and resolving customer complaints or issues. 
8.	Continuously monitoring customer satisfaction and retention metrics to track progress and make adjustments as needed. 
9.	Overall, the goal of customer retention is to create long-term customer loyalty, which helps generate a steady stream of repeat business and positive word-of-mouth advertising 


Data Preparation
- Grouping the data to check the customer type based on their sentiment.

Model Training
- Modelling : Kmeans Clustering, Agglomerative Hierarchical clustering algorithm, DBSCAN clustering algorithm



![image](https://user-images.githubusercontent.com/84577478/229334535-dd23f3fb-5b8e-48f9-9d85-5300d297cc2e.png)


CONCLUSION: 

- KMEANS Clustering has better silhouette score than other models, therefore it is best for clustering.  
- Customers having reviews with more than 0.6 sentiment score are most likely to be loyal customers and fall under CLUSTER 0 & 1. 
- Customers having reviews with less than 0.6 sentiment score are not likely to be repetitive customers and fall under CLUSTER 2. 
- Customers who are likely to be repetitive buyers (Cluster 0 & 2) are more than 50%. 
- Customers who belong to Cluster 1 have less sentiment score and are not likely to purchase again, so the products they purchased needs to be checked for Customer Retention Strategy.
- Products bought by customer having minimum average Sentiment score belonging to Cluster 1: 


