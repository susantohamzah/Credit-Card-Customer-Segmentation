# **Customer Segmentation Using Credit Card Usage Data**

## **Objective**
This project utilizes credit card usage data from a bank over the past six months to segment customers. By analyzing spending patterns, transaction frequency, and payment behavior, we aim to group customers into distinct segments. These segments can provide insights for personalized marketing, risk assessment, and tailored product offerings to enhance customer satisfaction and loyalty.

## **Background**
Customer segmentation is a crucial strategy for businesses to understand their customer base better and target them effectively. By dividing customers into distinct groups based on similar characteristics or behaviors, businesses can tailor their marketing efforts, improve customer satisfaction, and increase profitability.

## **Problem Solved**
Highly variable customer behaviors and preferences pose challenges for businesses in effectively targeting and serving their customers. By employing customer segmentation techniques, this project aims to address these challenges by identifying meaningful customer segments based on credit card usage data. This segmentation can help businesses personalize their marketing strategies, optimize product offerings, and enhance customer satisfaction and loyalty.

## **File Explanation**
- `P1G6_Set_1_agus_susanto.csv`: Dataset containing credit card usage data.
- `P1G6_Set_1_agus_susanto.ipynb`: Notebook for building the model, including data cleaning, data validation, exploratory data analysis (EDA), Principal Component Analysis (PCA), and building the model with KMeans clustering.
- `README.md`: Project overview and instructions.

## **Conclusion**
1. Based on PCA analysis, the data can be reduced from 18 features to 9 features with a data representation of 95%.
2. The model performs well with a total of 4 clusters.
3. The data exhibits a distributed pattern among clusters, although there are few instances where data overlaps into other clusters. Nevertheless, the number of clusters effectively categorizes the data.
4. A weakness of the model is the slight overlap of data distribution across different clusters, indicating the need to explore using 3 or 5 clusters to potentially improve results.

## **Tech Stack**
- **Programming Languages:** Python
- **Libraries/Frameworks:** Pandas, Scikit-learn, Matplotlib, Seaborn
- **Statistical Analysis:** KMeans Clustering, Principal Component Analysis (PCA)
