# Customer-Segmentation-using-KMeans-Clustering

# Project Overview:
This project applies KMeans clustering to segment mall customers into distinct groups based on their demographics and spending behavior. These insights enable data-driven marketing strategies, improve targeting, and enhance customer satisfaction.

# Customer Segmentation:
Customer segmentation is the practice of dividing a customer base into groups of individuals who share similar characteristics. These segments can be based on behavior, demographics, income, or spending patterns. Businesses use segmentation to better understand their customers and tailor offerings to meet their needs.

# KMeans Clustering Overview:
KMeans clustering is an unsupervised machine learning algorithm used to partition data into K distinct clusters. The algorithm assigns each data point to the nearest cluster centroid and iteratively refines these centroids until convergence. In this project, we use KMeans to identify customer groups based on annual income and spending scores.

# Dataset Overview:
The dataset consists of 200 observations and the following features: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100).
**Shape of dataset:** 200 rows × 5 columns

# Data Preview:
<img width="436" alt="image" src="https://github.com/user-attachments/assets/27199040-365b-4ce7-9ecb-6930d528be57" />

# Gender Distribution:

<img width="598" alt="image" src="https://github.com/user-attachments/assets/72dfb789-d184-4bfe-8198-0b9f7921daaa" />

The pie chart shows the proportion of male and female customers in the dataset.

# Customer Segmentation Visualizations:

Below are the cluster visualizations using different feature combinations:

**1. Income vs Spending Score:**

<img width="530" alt="image" src="https://github.com/user-attachments/assets/5f8f0345-d76d-4e0f-9157-f9c12f2721eb" />

**This visualization helps identify high-income, high-spending customers versus low-income, low-spending ones**

**2. Age vs Spending Score:**

<img width="541" alt="image" src="https://github.com/user-attachments/assets/ff16f048-614e-477f-8dde-55566adc4715" />

**Shows how spending activity varies across age groups, helping tailor strategies for younger vs. older customers.**

**3. Age vs Income:**

<img width="533" alt="image" src="https://github.com/user-attachments/assets/917db918-cf4d-4372-b8ef-c3b4eada8693" />

**Shows which age groups have higher incomes, aiding age-based targeting**

**4. 3D Customer Segmentation Scatterplot:**

<img width="893" alt="image" src="https://github.com/user-attachments/assets/26dd7ea6-15fa-4097-8b20-2fe80875aac2" />

3D scatter plot of customer clusters based on age, income, and spending score. Colors indicate clusters; black “X” marks centroids.

# **Conclusion:**

K-Means clustering has successfully segmented customers into distinct groups based on their age, income, and spending patterns. These insights provide a valuable foundation for targeted marketing strategies and improved customer engagement. The visualizations, including the 3D scatter plot, clearly illustrate the differences between clusters, empowering businesses to make data-driven decisions and tailor their approaches effectively.
