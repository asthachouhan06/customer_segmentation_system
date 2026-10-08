# SmartCart Customer Segmentation

Unsupervised learning system that groups SmartCart customers into segments based on their purchasing behavior, so the business can target marketing and offers.

## Problem Statement
Why segmentation is needed ??
SmartCart has thousands of customers but treats them all alike. This project finds natural groups to enable personalized marketing.

## Dataset
- Source: "smartcart_customers.csv"
- Size: <2240 x 22>
- Key features: age, income, response,spending,etc.

## Approach
1. Data cleaning (missing values, duplicates, outliers)
2. Exploratory data analysis
3. Feature scaling (StandardScaler)
4. Dimensionality reduction (PCA), if used
5. Clustering with K-Means / Hierarchical
6. Choosing the number of clusters (Elbow method, Silhouette score)
7. Profiling and interpreting each segment

## Results
| Segment | Description 
| 0 | low income, low spenders 
| 1 | catalog customers ,high spenders and high income
| 2 | digital browsers,low income, low spenders 
| 3 | premium customers but moderate spending

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Project Structure
```
├── data/            # dataset
├── notebooks/       # Jupyter notebooks
├── src/             # scripts
├── images/          # plots
├── requirements.txt
└── README.md
```

## How to Run
```
git clone https://github.com/asthachouhan06/customer_segmentation_system.git
cd <repo-name>
pip install -r requirements.txt
jupyter notebook
```


## Future Work
- Try other algorithms, deploy as a web app, add real-time data

## Author
Astha | asthachouhan06@gmail.com