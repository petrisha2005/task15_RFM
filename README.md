📊 Task 15 – Customer Segmentation (RFM Analysis)

📌 Project Overview
This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on an e-commerce transactional dataset.
RFM analysis helps businesses identify high-value customers and design targeted marketing strategies.

🎯 Objective
Clean transactional data
Calculate RFM metrics
Create RFM scores using quantile binning
Segment customers into meaningful groups
Generate business actions for each segment
Export segmentation results to CSV

📂 Dataset Used
Online Retail II Dataset (UCI Machine Learning Repository)
Contains transactional data of a UK-based online retail store.
Key columns used:
Invoice
InvoiceDate
Customer ID
Quantity
Price

🛠 Tools & Technologies
Python
Google Colab
Pandas
NumPy
Matplotlib


🔄 Steps Performed
Loaded Excel dataset
Removed cancelled invoices
Dropped missing Customer IDs
Converted InvoiceDate to datetime
Created TotalAmount column
Computed RFM metrics using groupby
Created RFM scores using quantile binning
Assigned customer segments
Visualized segment distribution
Exported results to CSV

🏷 Customer Segments
Segment	Description
Champions	:Recently purchased, frequent buyers, high spenders
Loyal	:Regular customers with good spending behavior
At Risk:	Previously frequent customers who have not purchased recently
Lost	:Customers inactive for long period
Others:	Moderate or low-value customers

📈 Business Actions
🏆 Champions
Exclusive premium offers
Loyalty rewards
Referral programs
❤️ Loyal
Cross-sell recommendations
Membership upgrades
Personalized marketing
⚠️ At Risk
Discount coupons
Reminder emails
Limited-time promotions
❌ Lost
Win-back campaigns
Feedback surveys
Special reactivation offers

📁 Project Deliverables
task15_rfm.ipynb → Complete analysis notebook
rfm_segments.csv → Customer segmentation output
segment_actions.txt → Business strategies per segment

📊 Outcome
This project demonstrates practical understanding of:
Customer behavior analysis
Data cleaning & preprocessing
Quantile-based scoring
Business-driven data segmentation
RFM segmentation can be directly used for targeted marketing, retention strategies, and revenue optimization.
