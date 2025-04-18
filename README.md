# Customer-Segmentation-in-E-commerce

 📌 Project Title
Customer Segmentation in E-commerce: Identifying customer clusters based on purchasing habits and browsing behavior.

🎯 Objective
To apply machine learning techniques to group (or "segment") customers of an e-commerce platform based on their numeric data such as purchase frequency, browsing time, and spending behavior. This helps businesses understand customer patterns and make data-driven marketing decisions.

📂 Dataset Description
Filename: 9. Customer Segmentation in E-commerce.csv
Data Format: CSV
Source: Provided as part of project
Contents: Customer-related numeric features such as:
Purchase history
Browsing behavior
Amount spent
Number of visits, etc.

🛠️ Tools & Libraries Used
Python (Google Colab)
Pandas – for data handling
NumPy – for numerical operations
Matplotlib & Seaborn – for data visualization
Scikit-learn – for clustering and PCA

🔍 Methodology
Data Loading: Dataset is uploaded into Google Colab.
Data Cleaning: Removed any rows with missing values.
Feature Selection: Selected only numerical columns for analysis.
Data Scaling: Standardized features using StandardScaler.
Clustering: Applied KMeans Clustering to segment the customers.
Elbow Method: Used to determine the optimal number of clusters (k).
Visualization: Used PCA (Principal Component Analysis) to reduce dimensions and visualize customer clusters in 2D.
Export: Final segmented data saved as a new CSV file.

📈 Output & Results
Customers are grouped into 4 clusters based on similarity.
A 2D scatter plot visualizes the clusters clearly.
Final dataset includes original data + Cluster, PCA1, PCA2 columns.
Output saved as: Customer_Segmentation_Output.csv

📊 Key Learnings
Hands-on experience with real-world data preprocessing
Learned how to apply unsupervised learning (KMeans)
Visualized customer patterns using PCA
Understood how customer segmentation is useful in marketing and business decisions

✅ Conclusion
This project successfully demonstrates how clustering techniques like KMeans can be used to segment customers in an e-commerce dataset. The approach helps businesses target specific groups for better marketing and improved user experience.

📄 References
Python documentation
scikit-learn library
Classroom resources and Google Colab notebooks
