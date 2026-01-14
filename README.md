# UK-Retail-Data-Analysis-Insights
This project analyzes a UK online retail store’s transactions to study customer behavior, segment customers using RFM, and automate segmentation with ML while estimating segment-level CLV.

## 🛠 Tools and Techniques used
- Python (NumPy, Pandas, Matplotlib, Scikit-learn)
- Google Colab
- Exploratory Data Analysis (EDA)
- RFM Analysis (Recency, Frequency, Monetary)
- Customer Segmentation
- Random Forest Classification
  
## 📂 Dataset Overview
- Transactional dataset from a UK-based online retail store
- ~541909 records  
- Features include invoiceno, stockcode, description, quantity, invoicedate, unitprice, customerid, and country.

## 📊 Exploratory Data Analysis
EDA was performed to understand business operations and spot data issues.
- Analyzed transaction trends over time
- Identifying top-selling and frequently returned products
- Tracked returns (negative quantities) and cancelled orders (invoice starting with “C”)
- Understanding customer activity and country-level distribution

## 📌 RFM Analysis
RFM  metrics were calculated at the customer level:
- **Recency:** Days since last purchase
- **Frequency:** Number of invoices
- **Monetary:** Total spending

Customers segmented into Champions, Loyal, Potential, At Risk, and Lost groups.

## 🤖 Machine Learning
- Automated customer segmentation using a Random Forest model
- Used RFM (Recency, Frequency, Monetary) values as input features
- Model assigns customers to predefined RFM segments
- Focused on simplifying customer grouping rather than predicting future behavior
- High performance is expected since the segments are directly derived from RFM values

## 🔍 Key Insights
- Returns account for **~2% of all transactions**, indicating low overall return volume.
- The **UK drives the majority of transactions**, making it the primary market.
- A significant portion of customers fall into **“At Risk”** and **“Potential” segments**, highlighting opportunities for re-engagement and retention.
- **RFM-based segmentation is consistent**, allowing clear identification of “At Risk” and “Lost” customers for targeted action.
- **Purchases peak during winter and festive months**, reflecting strong seasonal demand.

## 📍 Conclusion
This project presents an end-to-end customer analytics workflow, covering data cleaning, exploratory analysis, and RFM-based customer segmentation with machine learning automation.
It demonstrates how transactional data can be converted into actionable insights to improve retention, profitability, and business decision-making.

