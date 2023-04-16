# CryptoClustering

# BootCamp - Module 19 Challenge

Student Name - Anush De Costa Module 19 Challenge Name - CryptoClustering

## Introduction

This Module challenge was focused on using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. The project involved creating a new repository named CryptoClustering, loading the [crypto_market_data.csv](./Resources/crypto_market_data.csv) into a DataFrame, and using the StandardScaler() module from scikit-learn to normalize the data from the CSV file. The data was then prepared, and the best value for k was found using the elbow method. Finally, the cryptocurrencies were clustered with K-means using the original scaled data, and the clusters were optimized with Principal Component Analysis.

### - Elbow Curve for original Data

![Original Elbow](./images/original_elbow_bokeh_plot.png)

### - Elbow Curve for Principal Component Analysis Data

![Original Elbow](./images/PCA_elbow_bokeh_plot.png)

### - Elbow Curve Comparison

![Original Elbow](./images/elbow_comparison_bokeh_plot.png)

### - Cluster plot of cryptocurrency based on the original data

![Original Elbow](./images/original_scatter_bokeh_plot.png)

### - Cluster plot of cryptocurrency based on the Principal Component Analysis Data

![Original Elbow](./images/PCA_scatter_bokeh_plot.png)

## Conclution

As per the above images it is clear that Principal Component Analysis Data allows for a lower inertia and results in a more distinct cluster than using the original data. This suggests that the PCA model contains less noise and greater separability compared to the original model.

## Tools

- Jupyter Notebook
- Python
- pandas
- NumPy
- scikit-learn
- hvPlot

## Main File

-[Jupyter Notebook](/Crypto_Clustering.ipynb)
