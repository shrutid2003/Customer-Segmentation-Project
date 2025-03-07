# Customer-Segmentation-Project
Customer Segmentation Project using KMeans Clustering

Overview

This project applies KMeans clustering to a marketing campaign dataset to segment customers based on their behavior and purchasing habits. The goal of the project is to help identify distinct customer groups for targeted marketing strategies. The project also includes Exploratory Data Analysis (EDA) to understand patterns in the data before clustering.

Dataset

The dataset used for this project is named marketing_campaign.csv and contains information about customers, such as their demographic details and purchasing habits. This data helps to perform clustering and gain insights into customer segments.


Columns in the dataset include:

ID: Unique customer ID
Year_Birth: Year of birth of the customer
Education: Level of education
Marital_Status: Marital status of the customer
Income: Annual income of the customer
Dt_Customer: Date of enrollment in the company
Recency: Number of days since last purchase
MntWines, MntFruits, etc.: Amount spent on different products
NumDealsPurchases, NumWebPurchases, etc.: Number of purchases made through different channels


Technologies Used
Python: Programming language used for the project
Pandas: For data manipulation and analysis
Matplotlib & Seaborn: For data visualization and plotting
Scikit-learn: For implementing the KMeans clustering algorithm
Yellowbrick: For visualizing the KMeans elbow method
Jupyter Notebook: For running the project code


Project Steps
1. Data Preprocessing
Handled missing data.
Converted the Dt_Customer column to datetime format.
Created new features, such as customer age and tenure.
2. Exploratory Data Analysis (EDA)
Explored customer distribution across age, income, and other demographic features.
Visualized the spending patterns on various products.
Created a correlation heatmap to understand feature relationships.
3. KMeans Clustering
Used the Elbow method to determine the optimal number of clusters.
Performed KMeans clustering to group customers into segments.
Analyzed and interpreted the characteristics of each customer segment.
4. Results & Insights
Segmented customers into groups based on spending behavior and demographics.
Identified potential strategies for targeted marketing based on customer groups.




Conclusion

This project showcases customer segmentation using KMeans clustering to understand customer behavior and purchasing patterns. The insights generated from the project can help businesses tailor their marketing strategies to different customer segments.
