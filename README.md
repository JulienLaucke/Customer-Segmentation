# Customer Segmentation using K-Means Clustering

## Project Overview
This project aims to segment customers of a mall into distinct groups using the K-Means clustering algorithm. The goal is to understand customer behavior better and to develop targeted marketing strategies.

## Data
The dataset used for this project is the `Mall_Customers.csv` file, which contains the following columns:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: Spending score assigned by the mall based on customer behavior and spending nature

## Project Steps

1. **Data Preparation**:
    - Loading the data.
    - Checking for missing values and outliers.

2. **Feature Engineering**:
    - Selecting relevant features for clustering: Age, Annual Income, and Spending Score.

3. **Exploratory Data Analysis (EDA)**:
    - Visualizing the data to understand the distribution and relationships between the features.

4. **K-Means Clustering**:
    - Using the Elbow Method to determine the optimal number of clusters.
    - Applying the K-Means clustering algorithm with the optimal number of clusters.

5. **Cluster Analysis**:
    - Interpreting and naming the clusters based on their characteristics.
    - Visualizing the clusters and their main features.

6. **Dashboard Creation**:
    - Developing an interactive dashboard using Plotly to visualize the cluster analysis and customer segments.

7. **Results and Recommendations**:
    - Summarizing the results and providing recommendations for targeted marketing strategies.

## Requiertments

To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- matplotlib
- plotly
- scikit-learn
