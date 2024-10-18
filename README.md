# LRFMV-Analysis
Adding Length and Volume to RFM equation

### Introducing LRFMV: An Enhanced Segmentation Model
While the RFM (Recency, Frequency, Monetary) model has long been a staple in customer segmentation, I tried to explore an enhanced version: the LRFMV model. This model adds two crucial dimensions:

![image](https://github.com/user-attachments/assets/2951e30f-0cbf-4e2b-b713-f1d50203cf55)

### Dataset Overview
Our analysis utilizes transactional data from Walmart retail stores spanning 2012–2015. The dataset comprises:

Order Details: Order ID, Date, Shipping Method
Product Info: Items, Categories
Customer Info: Customer ID, Segment, Location
Financials: Sales, Quantity, Profit, Discount

No of records: 8,399 

### Key Steps in Analysis
Data Preparation: Imported necessary libraries and loaded the dataset.
Calculating LRFMV Metrics: Calculated Length, Recency, Frequency, Monetary value, and Volume for each customer.
Customer Segmentation: Customers were assigned scores based on their LRFMV metrics and categorized into segments such as "Champions," "Loyal Customers," "At Risk," and more.
Segment Analysis: Examined the distribution of customers across segments and their contribution to revenue.
LRFMV Correlation Analysis: Explored relationships between different LRFMV metrics across segments.
Volume-Profit Relationship: Investigated how volume relates to profitability in different customer segments.

### Key Findings and Insights
### Customer Segment Distribution
![image](https://github.com/user-attachments/assets/3e4b0d81-2e1f-4fe5-9524-d990a5ce3bf6)
![image](https://github.com/user-attachments/assets/ab9a0019-259f-4640-a1b0-1d0fbd72803e)

The analysis revealed some striking insights:

The "About to Lose" and "At Risk" segments dominate, comprising over 60% of the customer base. This indicates a high churn risk and necessitates immediate attention.
"Promising Customers," while only 10.4% of the customer base, contribute 19.6% of revenue, showing high growth potential.
"Loyal Customers," though the smallest segment at 0.4%, deliver 1.7% of revenue, emphasizing the importance of customer loyalty.

### LRFMV Correlation Analysis
![image](https://github.com/user-attachments/assets/5ccd1220-36e5-4657-98ac-7a5ea6ab9d87)

Here I have examined relationships between different LRFMV metrics across segments:

Recency vs. Frequency: As expected, more recent customers tend to have higher purchase frequency.
Length vs. Volume: Longer-term customers don't necessarily purchase in higher volumes.
Monetary vs. Volume: Higher volume doesn't always correlate with higher monetary value, suggesting potential for targeted pricing strategies.

Including Volume (V) in RFM analysis shifts focus to quantity purchased, allowing businesses to identify high-volume buyers and increase their profitability. The 'V' in LRFMV enables more nuanced strategies for improving profitability across segments, helping understand why customers are valuable and how to enhance that value.

### Actionable Strategies
Based on our analysis, here are some targeted strategies for each segment:

* Implement targeted retention campaigns for the "About to Lose" segment.
* Develop re-engagement strategies for the "At Risk" segment, possibly through personalized offers or reminders.
* Focus on nurturing "Promising Customers" to convert them into loyal customers through enhanced customer experiences and loyalty programs.
* Investigate ways to increase average order value for "High Volume Customers," possibly through bundle offers or volume discounts.
* Create personalized loyalty programs to retain and grow the "Loyal Customers" segment, emphasizing their value to the company.
* For "Potential Loyalists," develop strategies to increase their purchase frequency and monetary value, possibly through targeted promotions or exclusive offers.

Note: For a detailed exploration of the LRFMV model and its implementation, including code examples and visualizations, please check out my full article originally published on Medium: https://medium.com/learning-data/beyond-rfm-how-volume-enhances-customer-understanding-6dc0e9b8ee3f.
  
  

