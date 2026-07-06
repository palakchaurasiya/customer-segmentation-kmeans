# Customer Segmentation using K-Means Clustering

## Project Description
In this project, I performed Customer Segmentation using K-Means Clustering algorithm on Mall Customers Dataset to identify different groups of customers based on their spending behavior.

## Dataset Details
- **File**: Mall_Customers.csv
- **Features Used**: Annual Income (k$) and Spending Score (1-100)

## Methodology
1. Data Loading and Preprocessing
2. Feature Scaling using StandardScaler
3. K-Means Clustering with k=5
4. Visualization using Seaborn and Matplotlib

## Segments Identified
1. **VIP - Target**: High Income, High Spending
2. **Standard**: Medium Income, Medium Spending
3. **Careful**: High Income, Low Spending
4. **Sensitive**: Low Income, High Spending
5. **Need-Focus**: Low Income, Low Spending

## Tools and Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Output Files
- `segmentation_chart.png`: Scatter plot showing customer segments
- `Segmented_Customers.csv`: Dataset with assigned segment labels
- `Customer_Segmentation.ipynb`: Complete Jupyter Notebook code
