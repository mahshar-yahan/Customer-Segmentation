# Customer Segmentation Using K-Means and Hierarchical Clustering

This project focuses on customer segmentation by applying K-Means and hierarchical clustering techniques. The goal is to group customers based on key attributes, enabling better understanding and targeted marketing strategies.

## Dataset

The dataset used for this project contains the following features:

- **Customer ID:** Unique identifier for each customer
- **Age:** Age of the customer
- **Gender:** Gender of the customer
- **Annual Income:** Annual income of the customer (in currency units)
- **Spending Score:** Spending score based on customer behavior and purchasing patterns

## Project Overview

Customer segmentation is crucial for businesses to tailor their marketing efforts and improve customer satisfaction. In this project, we use K-Means and hierarchical clustering to segment customers into distinct groups based on their demographic and financial characteristics.

### Key Features

- **K-Means Clustering:** Groups customers into k clusters based on similarities in their attributes.
- **Hierarchical Clustering:** Provides a tree-like structure of clusters, enabling more detailed customer segmentation.
- **Visualization:** Plots and visualizes the clustering results for better interpretation.

## Data Preprocessing

- **Handling Missing Values:** Checked for and handled any missing values in the dataset.
- **Normalization:** Scaled features like age, annual income, and spending score to ensure uniformity in clustering.
- **Encoding:** Encoded categorical features like gender into numerical values for clustering.

## Clustering Techniques

### K-Means Clustering

- **Initialization:** Determined the optimal number of clusters using the elbow method.
- **Execution:** Applied the K-Means algorithm to segment customers into clusters.
- **Visualization:** Used scatter plots to visualize the clusters based on different feature pairs.

### Hierarchical Clustering

- **Dendrogram Analysis:** Used dendrograms to determine the optimal number of clusters.
- **Execution:** Applied agglomerative hierarchical clustering to group customers.
- **Visualization:** Visualized the hierarchical clusters using dendrograms and scatter plots.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Scipy

### Installation

Clone the repository:
```bash
https://github.com/mahshar-yahan/Customer-Segmentation.git
cd customer-segmentation
