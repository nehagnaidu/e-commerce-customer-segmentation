 # **E-Commerce Customer Segmentation using RFM, K-Means & PCA**
### **By Neha G Naidu**
 ****

**Basic Overview**<br>
This project aims to analyze customer purchasing behavior for an online retail store using transaction data. By applying RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, customers are segmented into distinct groups based on their buying patterns. This segmentation enables businesses to implement targeted marketing strategies tailored to each customer group.

**Objective of the Analysis**<br>
  - Analyze customer purchasing behavior using RFM metrics
  - Segment customers into distinct groups using K-Means clustering
  - Gain actionable insights to support personalized marketing and improve business performance

**Libraries Used**<br>
- **pandas** – for data manipulation and RFM feature creation  
- **matplotlib** – for visualizing trends and cluster distributions  
- **seaborn** – for plots
- **scikit-learn (sklearn)** – for:
  - StandardScaler (data normalization)
  - KMeans (clustering)
  - PCA (dimensionality reduction for visualization)

## **About DataSet**
****
**Type**: A Real-world e-commerce transaction data from a UK-based online retail store.

**Source**: [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data) (originally from the UCI Machine Learning Repository)

**Transactions**: Over 500,000

**Key Features**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**Time period**: December 2010 to December 2011

**Products**: Unique, all-occasion gift items

**Customers**: Imcludes both individual buyers and wholesalers

