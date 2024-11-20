Clustering Donor Behavior in Nonprofit Transactions

Project Overview

This project focuses on analyzing transactional donation data to identify distinct donor segments using the K-means clustering algorithm. By understanding donor behavior, nonprofits can develop tailored engagement strategies to improve donor retention and optimize fundraising efforts.

Objectives

	•	To explore donation patterns and donor behavior.
	•	To apply K-means clustering for segmenting donors based on their recency, frequency, and monetary value.
	•	To provide actionable insights for nonprofit organizations to enhance their fundraising strategies.

Dataset

	•	Source: [Describe the source of the data, e.g., simulated data, anonymized real data].
	•	Fields:
	•	donor_id: Unique identifier for each donor.
	•	close_date: Date of the donation.
	•	donation_amount: Value of the donation.
	•	Engineered Fields:
	•	Recency: Days since the last donation.
	•	Frequency: Number of donations in a specific period.
	•	Monetary Value: Total donation amount.

Technologies Used

	•	Programming Language: Python
	•	Libraries:
	•	Data Manipulation: Pandas, NumPy
	•	Data Visualization: Matplotlib, Seaborn
	•	Machine Learning: Scikit-learn
	•	Development Environment: Jupyter Notebook

Steps Followed

	1.	Data Preprocessing:
	•	Cleaned the dataset by handling missing values and outliers.
	•	Normalized features for clustering.
	2.	Exploratory Data Analysis (EDA):
	•	Visualized donation trends, recency, frequency, and monetary distributions.
	3.	Feature Engineering:
	•	Created features like Recency, Frequency, and Monetary Value for clustering.
	4.	K-means Clustering:
	•	Determined the optimal number of clusters using the Elbow method.
	•	Segmented donors into distinct clusters.
	5.	Cluster Analysis:
	•	Interpreted each cluster and its characteristics.
	6.	Recommendations:
	•	Suggested personalized strategies for donor engagement based on cluster insights.

Key Insights

	•	Donors were segmented into [e.g., “high-value donors,” “frequent donors,” “low-engagement donors”].
	•	Strategies for engagement vary significantly between clusters, enabling nonprofits to allocate resources more effectively.

How to Run the Project

	1.	Clone the repository:

    