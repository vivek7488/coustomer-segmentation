# 🎯 Customer Segmentation Project

Overview

This Customer Segmentation Project aims to classify and group customers into distinct segments based on purchasing behaviors and other key attributes. The insights derived from this segmentation allow businesses to target their marketing efforts, improve customer retention, and personalize services to meet specific customer needs.

# Key Objectives

1.📊 Segment Customers: Group customers into meaningful clusters based on purchase history, demographics, and behavior.

2.🔍 Understand Customer Profiles: Gain insights into each customer group’s characteristics to drive personalized marketing strategies.

3.📈 Improve Business Decision-Making: Use segmentation data to tailor offerings, increase sales, and enhance customer satisfaction.

# Features
1. Data Preprocessing :
     Cleaning and transforming raw data for analysis.
     Handling missing values and outliers to ensure data quality.
3. Exploratory Data Analysis (EDA) :
     Visualization of customer behavior across various features (age, spending patterns, frequency of purchases).
     Insights into how different attributes contribute to customer segmentation.
4. Clustering Techniques :
     Implementation of algorithms like K-Means, Hierarchical Clustering, and DBSCAN to group customers into segments.
     Elbow method and Silhouette Score used to determine optimal cluster numbers.
5. Customer Profile Creation :
     Each segment is profiled based on spending habits, purchase frequency, and demographics.
     Easy identification of high-value customers, discount seekers, and infrequent shoppers.
6. Visualization of Segments :
     Interactive charts and graphs to showcase customer distribution across different segments.
     Heatmaps, scatter plots, and bar charts used to visualize cluster characteristics.


# Technology Stack

1. Programming Languages: Python
2. Libraries:
3. Data processing: ![image](https://github.com/user-attachments/assets/20cde355-d60c-4fa2-a4ce-abf1069c1816)
 ![image](https://github.com/user-attachments/assets/53d91606-bd79-4ca9-948a-c9390fd88abf)

4. Visualization:
![image](https://github.com/user-attachments/assets/68d8f86f-18b3-4dc7-b9da-6ee2b791b09c)
5. Clustering: scikit-learn
6. Jupyter Notebook: Used for code development and documentation.


# Data Source

1.Transaction Data: Includes customer ID, age, gender, total spending, purchase frequency, and product categories.

2.Demographics: Gender, age group, location.

3.Customer Behavior: Average transaction value, frequency of transactions.

# Sample Data Columns

1.Customer ID: Unique identifier for each customer.

2.Age: Age of the customer.

3.Gender: Gender (Male/Female).

4.Annual Income: Total annual earnings.

5.Spending Score: A score assigned based on spending habits (0-100).

6.Purchase Frequency: How often the customer makes purchases.


# Clustering Methodology

1. Data Scaling: Standardize features using StandardScaler to normalize data and eliminate bias from differences in scale.

2. K-Means Clustering:
    Applied to identify distinct customer groups.
    The Elbow Method and Silhouette Score were used to determine the optimal number of clusters.


# Visualizations

1.Customer Segmentation Distribution: Displays how customers are spread across different segments.

2.Customer Profiles: Bar charts and scatter plots representing key attributes for each segment (e.g., spending score vs. income).

3.Cluster Heatmaps: Visualize relationships between different attributes within clusters.


# Results
The customer segmentation reveals the following key groups:

1.High-Spenders: Customers who have a high annual income and make frequent, large purchases.

2.Discount Seekers: Customers who tend to purchase only during sales and promotions.

3.Infrequent Shoppers: Customers who make sporadic purchases with low spending amounts.

3.Loyal Customers: Regular purchasers who maintain moderate spending but high engagement.


# Future Enhancements
1.🧠 Advanced Segmentation: Incorporate additional machine learning models, such as Gaussian Mixture Models and Deep Learning approaches, to refine segmentation.

2.🔄 Real-Time Segmentation: Implement a system to analyze customer behavior in real-time using streaming data.

3.📲 Personalization Recommendations: Leverage customer segments for recommending personalized products and marketing strategies.

# Screenshots

![image](https://github.com/user-attachments/assets/2cbcb1eb-ac2a-4698-b90a-254d4bd6df4b)

![image](https://github.com/user-attachments/assets/f221b9b7-1b1c-4989-bf1e-18debb47a5e3)

