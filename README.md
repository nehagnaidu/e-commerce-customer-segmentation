 # **E-Commerce Customer Segmentation using RFM, K-Means & PCA**
### ***By Neha G Naidu***
 ****

**Basic Overview**<br>

*This project aims to analyze customer purchasing behavior for an online retail store using transaction data. Using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering**, customers are segmented into distinct groups to support **personalized marketing, customer retention, and business growth.*** <br>
***Techniques used***: *Data cleaning, exploratory data analysis (EDA), feature engineering, clustering, and visualization.*

**Objective of the Analysis**

  - *Analyze **customer purchasing behavior** using **RFM metrics***
  - *Segment customers into distinct groups using **K-Means clustering***
  - *Gain actionable insights to support **personalized marketing** and **improve business performance***

**🛠️ Tech Stack**<br>

**Languages**: *Python*<br>
**Libraries**: *pandas, numpy, matplotlib, seaborn, scikit-learn*<br>
**Techniques**: *RFM Analysis, K-Means Clustering, PCA (Dimensionality Reduction)*<br>
**Dataset**: [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data) (originally from the UCI Machine Learning Repository)

**📂 Dataset Details**<br>

**Transactions**: *~541,909*<br>
**Customers**: *~4,300 unique customers*<br>
**Time period**: *Dec 2010 – Dec 2011*<br>
**Features**: *InvoiceNo, StockCode, Description, Quantity, UnitPrice, InvoiceDate, CustomerID, Country*<br>
**Products**: *Unique, all-occasion gift items*<br>
**Customers**: *Includes both individual buyers and wholesalers*

**🔍 Data Preprocessing**<br>
- *Removed missing **CustomerID** and **Description** entries (~25%).*
- *Filtered **invalid** transactions (negative quantities & prices).*
- *Added **TotalPrice** feature (Quantity × UnitPrice).*

**📊 Exploratory Data Analysis (EDA)**<br>

**Key insights**:
- **Net Revenue**: *£8.3M+*<br>
- **Items Sold**: *5.1M+*<br>
- **Top Country**: *UK (~90% of revenue)*<br>
- **Top Products**: *Paper Craft, Little Birdie, Regency Cake Stand*<br>
- **Trends**: *Post-holiday dip (Jan–Feb), peak in Q4 (Sep–Nov)*.<br>

<img width="696" height="408" align="centre" alt="image" src="https://github.com/user-attachments/assets/312c083a-09a9-438a-8909-37f4fba31880" />
<img width="600" height="440" align="centre" alt="image" src="https://github.com/user-attachments/assets/311ad6c9-f8c2-44a8-be1e-ebedac66c89d" /><br>

<img width="306" height="339" align="centre" alt="image" src="https://github.com/user-attachments/assets/57afa533-e15f-459a-99ff-c4e37e217920" />

**🤖 Customer Segmentation (K-Means)**<br>
- *Used Elbow Method → optimal k=4.*

Segmented customers into 4 groups:<br>

| Cluster | Label                | Characteristics                 | Strategy                 |
| ------- | -------------------- | ------------------------------- | ------------------------ |
| 0       | Occasional Buyers    | Low frequency, medium spend     | Nurture with offers      |
| 1       | Frequent Buyers      | Regular purchases, steady spend | Upsell & loyalty rewards |
| 2       | High-Value Loyalists | Recent, frequent, high spend    | Retain with VIP perks    |
| 3       | Dormant Customers    | Long inactive, low spend        | Re-engagement campaigns  |

<img width="500" height="340" alt="image" src="https://github.com/user-attachments/assets/1d579101-7148-46ce-b94f-826f4d5abc74" />


**📈 Key Findings**<br>

- *Revenue is highly UK-concentrated, international markets underperform.*
- *Strong Q4 sales surge, weak Q1 demand.*
- *A few key products drive revenue disproportionately.*
- *Customer base includes valuable loyalists, but many are at risk of churn.*

**💡 Recommendations**<br>

- ***Retain High-Value Loyalists** → loyalty programs, exclusive offers.*
- ***Upsell Frequent Buyers** → personalized recommendations, cart reminders.*
- ***Convert Occasional Buyers** → welcome campaigns, discounts.*
- ***Reactivate Dormant Customers** → win-back emails, time-limited incentives.*
- ***Expand internationally** → test marketing in top 2–3 foreign markets.*


