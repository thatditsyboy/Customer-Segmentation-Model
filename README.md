# Customer-Segmentation-Model

## Project Overview
This project focuses on customer segmentation of credit card holders based on their spending and usage behaviors. The goal is to identify distinct customer groups to enable banks to perform targeted marketing, enhance customer engagement, and optimize resource allocation.

## Dataset
The dataset used contains information on credit card holders, including:
- **CUST_ID**: Unique identifier for each customer
- **BALANCE**: Balance amount
- **PURCHASES**: Total purchase amount
- **ONEOFF_PURCHASES**: Amount for one-off purchases
- **INSTALLMENTS_PURCHASES**: Amount for installment-based purchases
- **CASH_ADVANCE**: Cash advance amount
- **CREDIT_LIMIT**: Credit limit for each customer
- **TENURE**: Number of months the customer has been with the bank

For a full list of features, refer to the project files.

## Project Structure
The repository contains the following files and directories:
- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks with data analysis, preprocessing, and model development.
- `scripts/`: Python scripts for preprocessing, model training, and evaluation.
- `results/`: Outputs and visualizations from clustering analyses.
- `README.md`: Overview of the project.

## Methodology
1. **Data Preprocessing**: Handle missing values, standardize features, and analyze data distribution.
2. **Exploratory Data Analysis (EDA)**: Examine data trends, correlations, and distributions to understand key features.
3. **Clustering Algorithms**: Implemented K-Means and DBSCAN algorithms to segment customers into clusters.
4. **Cluster Evaluation**: Used silhouette score and elbow method to assess clustering quality and determine the optimal number of clusters.
5. **Cluster Profiling**: Analyzed each cluster's characteristics to define customer segments based on spending patterns, credit usage, and frequency.

## Requirements
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-Model.git
   cd Customer-Segmentation-Model

## Usage
Run notebooks/Customer_Segmentation.ipynb to execute data preprocessing, clustering, and evaluation steps.
Adjust parameters and evaluate clustering models based on the insights and scores obtained.

## Results
The K-Means clustering algorithm identified six key customer segments, including:
1. High-Spending, High-Balance Customers
2. Installment-Heavy Customers
3. Cash Advance Users
4. Low-Spending, Low-Balance Customers & more
Visualizations of each cluster are provided in the results/ directory to highlight distinctive behaviors across these segments.

## Conclusion
The segmentation model successfully identified distinct customer groups, offering valuable insights for targeted marketing strategies. By understanding customer behaviors, banks can now tailor their marketing and engagement efforts to maximize customer satisfaction and optimize resource distribution.

