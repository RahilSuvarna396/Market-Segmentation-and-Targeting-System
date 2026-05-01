# Market Segmentation and Targeting System

## Project Overview

This project presents a data-driven Market Segmentation and Targeting System designed for a retail company to better understand its customers and optimize marketing strategies.

Using clustering techniques, the system groups customers based on demographics, income, and spending behavior, enabling personalized marketing and improved decision-making.

---

## Problem Statement

Retail companies often run generic marketing campaigns that fail to engage diverse customer groups. Differences in customer demographics, purchasing behavior, and spending patterns make it difficult to identify high-value customers and target them effectively.

This project addresses the problem by:

* Segmenting customers into meaningful groups
* Identifying high-value and potential customers
* Recommending targeted marketing strategies
* Improving marketing ROI through data-driven insights

---

## Dataset

* Name: Mall Customer Segmentation Dataset
* Source: Kaggle
* Features:

  * CustomerID
  * Gender
  * Age
  * Annual Income (k$)
  * Spending Score (1-100)

---

## Techniques and Algorithms Used

### Machine Learning Models

* K-Means Clustering
* Hierarchical Clustering (Agglomerative)

### Data Processing

* Feature Engineering (Spending Efficiency)
* Feature Scaling (StandardScaler)

### Validation

* Silhouette Score for cluster evaluation

### Visualization

* Elbow Method for optimal cluster selection
* Scatter plots for cluster visualization
* Pairplots for multi-feature analysis
* Heatmaps for correlation analysis

---

## Tools and Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Project Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Feature Engineering
4. Feature Scaling
5. K-Means Clustering
6. Hierarchical Clustering
7. Cluster Validation using Silhouette Score
8. Data Visualization
9. Cluster Interpretation
10. Strategy Recommendation

---

## Results

* Identified 5 distinct customer segments
* K-Means performed better based on silhouette score
* Customers grouped based on income, age, and spending patterns

### Sample Cluster Types

* High Income – High Spending: Premium Customers
* High Income – Low Spending: Target for upselling
* Low Income – High Spending: Impulsive buyers
* Low Income – Low Spending: Low priority
* Mid-range Customers: Average segment

---

## Key Insights

* Income alone does not determine spending behavior
* Some low-income customers spend more than expected
* High-income customers are not always high spenders
* Targeted marketing is essential for improving engagement

---

## Marketing Strategy Recommendations

| Segment             | Strategy                            |
| ------------------- | ----------------------------------- |
| High Spenders       | Premium offers, loyalty programs    |
| Potential Customers | Discounts and targeted promotions   |
| Impulsive Buyers    | Flash sales and limited-time offers |
| Low Value Customers | Minimal marketing investment        |
| Mid-range Customers | Engagement campaigns                |

---


## Evaluation Metrics

* Silhouette Score (K-Means): Measures cluster quality
* Silhouette Score (Hierarchical): Used for comparison

Higher score indicates better-defined clusters.

## Author
Rahil R
MSc Data Science / Analytics

