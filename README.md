# Clustering Donor Behavior in Nonprofit Transactions

## Project Overview
This project focuses on analyzing transactional donation data to identify distinct donor segments using the K-means clustering algorithm. By understanding donor behavior, nonprofits can develop tailored engagement strategies to improve donor retention and optimize fundraising efforts.

## Objectives
- To explore donation patterns and donor behavior.
- To apply K-means clustering for segmenting donors based on their recency, frequency, and monetary value.
- To provide actionable insights for nonprofit organizations to enhance their fundraising strategies.

## Dataset
- **Source:** [Describe the source of the data, e.g., simulated data, anonymized real data].
- **Fields:**
  - `donor_id`: A unique identifier for each donor. This field helps to track individual donors across multiple donations.
  - `donation_date`: The date when the donation was made. Useful for analyzing donation trends over time.
  - `payment_type`: The method used for the donation (e.g., Credit Card, Cash). Useful for understanding payment preferences among donors.
  - `donation`: The amount donated by the donor in a specific transaction. Important for tracking the financial contribution of each donor.
  - `campaign`: The specific fundraising campaign associated with the donation. Useful for analyzing which campaigns are most effective or popular.
  - **Engineered Fields:**
    - `recency`: Days since the last donation by donor.
    - `frequency`: Number of donations in a specific period by donor.
    - `total_donations`: Total donation amount by donor.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Data Manipulation: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
- **Development Environment:** Jupyter Notebook

## Steps Followed
1. **Data Preprocessing:**
   - Cleaned the dataset by handling missing values and outliers.
   - Normalized features for clustering.
2. **Exploratory Data Analysis (EDA):**
   - Visualized donation trends, recency, frequency, and monetary distributions.
3. **Feature Engineering:**
   - Created features like Recency, Frequency, and Monetary Value for clustering.
4. **K-means Clustering:**
   - Determined the optimal number of clusters using the Elbow method.
   - Segmented donors into distinct clusters.
5. **Cluster Analysis:**
   - Interpreted each cluster and its characteristics.
6. **Recommendations:**
   - Suggested personalized strategies for donor engagement based on cluster insights.

## Key Insights
- Donors were segmented into [e.g., "high-value donors," "frequent donors," "low-engagement donors"].
- Strategies for engagement vary significantly between clusters, enabling nonprofits to allocate resources more effectively.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/jamonhin/Non-profit-project

2. Navegate to the directory:
    ```bash
    cd donor-clustering

3. Install dependencies:
    ```bash
    pip install -r requirements.txt

4.	Open the Jupyter Notebook:
    ```bash
    jupyter notebook
