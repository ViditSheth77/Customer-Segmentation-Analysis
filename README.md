# 📊 Customer Segmentation Analysis
A complete pipeline for customer segmentation using RFM analysis (Recency, Frequency, Monetary), clustering with KMeans, visualizations, and NLP-based sentiment analysis. This project provides insights into customer behavior and uses machine learning techniques for segmentation and predictive modeling.

## 🚀 Features
RFM Analysis to classify customers based on their purchase behavior.
KMeans Clustering to group customers into segments.
Data Visualizations using Seaborn, Matplotlib, and Plotly.
Sentiment Analysis with VADER and TextBlob to analyze customer reviews.
WordCloud Generation for visualizing text data.
Logistic Regression for predicting repurchases.
Dash Integration for building interactive dashboards (optional).
## 🗂️ Dataset
The dataset is sourced from Kaggle's <a href="https://www.kaggle.com/datasets/carrie1/ecommerce-data?select=data.csv">Ecommerce Data</a> and contains transactional records from a UK-based online retailer.
## 📋 Requirements
Make sure you have the following packages installed:
bash
```
pip install pandas scikit-learn matplotlib seaborn plotly dash nltk textblob wordcloud kagglehub
```

🔧 Installation and Usage
Clone the repository:
bash

```
git clone https://github.com/your-username/customer-segmentation.git
cd customer-segmentation
```


Run the notebook locally:
Open Google Colab or Jupyter Notebook.
Load the Customer Segmentation Analysis.ipynb notebook.
Dataset Download:
Download the dataset using the KaggleHub API:

```
import kagglehub
path = kagglehub.dataset_download("carrie1/ecommerce-data")
```

# 🧠 Project Overview

1. Data Cleaning and Preprocessing
Drop rows with missing customer IDs.
Filter out invalid transactions (quantities or prices ≤ 0).
Create a TotalPrice column (Quantity × UnitPrice).

2. RFM Analysis
RFM analysis groups customers based on:
Recency: Days since the last purchase.
Frequency: Number of purchases.
Monetary: Total spending.

3. KMeans Clustering
Standardize RFM values using StandardScaler.
Apply KMeans clustering to segment customers into 3 or 4 clusters.

4. Data Visualizations
Seaborn Scatterplots to show RFM clusters.
Monthly Revenue Trend and Top Purchased Products.
Heatmaps for correlation between features.

6. Sentiment Analysis with NLP
Use VADER and TextBlob for sentiment scores.
Generate WordClouds for customer feedback.

7. Machine Learning for Predictive Analytics
Apply Logistic Regression to predict repurchases.
Evaluate model performance using a Confusion Matrix and Classification Report.


# 📊 Key Visualizations
-3D Cluster Plot of Customer Segments.<br>
-Top 10 Countries by Revenue.<br>
-Monthly Revenue Trend.<br>
-WordCloud of customer reviews.<br>

## 📝 Usage of Sentimernt Analysis
<img width="826" alt="Screenshot 2024-10-17 at 3 11 03 PM" src="https://github.com/user-attachments/assets/0757b2e9-e125-4e60-ac28-4d03b0a0607b">

## 📈 Example Visualizations

- Monthly Revenue Trend:
  <img width="1017" alt="Screenshot 2024-10-17 at 3 11 44 PM" src="https://github.com/user-attachments/assets/79732c5f-ae87-4170-9af4-64abeb1b5b8e">
  
- Top 10 Most Purchased Products:
  <img width="1264" alt="Screenshot 2024-10-17 at 3 11 59 PM" src="https://github.com/user-attachments/assets/4ae950ed-90bc-41a4-864a-9cc922c9dfb6">

- 3D view of Customer Segment

https://github.com/user-attachments/assets/9552af70-828c-425e-b96f-46d34ae4eb5c


  
- Customer Segmentation with K-Means
  <img width="724" alt="image" src="https://github.com/user-attachments/assets/ab2d827f-b0a7-4f87-9896-03d01d5396ac">

- Sales Forecast using ARIMA
  <img width="824" alt="image" src="https://github.com/user-attachments/assets/057f0dea-0888-471b-bcb8-105a5424d511">



# 🎯 Future Improvements
Add Dash App for interactive dashboards.
Explore other clustering methods like DBSCAN or Hierarchical Clustering.
Enhance predictive analytics with Random Forest or XGBoost models.
Deploy the analysis on a cloud platform for live monitoring.

# 🤝 Contributing
Feel free to fork this repository and submit pull requests to enhance the project!

# 🧑‍💻 Author
Vidit Sheth

# 💬 Feedback
If you have any questions or feedback, feel free to reach out via GitHub Issues.

# 🔗 Links
Kaggle Dataset: https://www.kaggle.com/datasets/carrie1/ecommerce-data?select=data.csv <br>
Project Notebook on Colab: https://colab.research.google.com/drive/1oYqfi7Q9h-XClifhAD-yGAAD_wurIg0w?usp=sharing

