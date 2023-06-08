# Cryptocurrency Clustering: An Unsupervised Learning Approach

![cryptocurrency-Nuthawut-adobe](https://github.com/AnushDeCosta/ML-Cryptocurrency-Clustering/assets/67308030/8ee1688c-e315-4a6a-98ee-eb2f069765ac)

## Introduction

In this analysis, the emphasis was on leveraging Python and unsupervised learning techniques to predict how cryptocurrencies respond to fluctuations in price over a span of 24 hours or 7 days. The project encompassed creating a novel repository termed as 'CryptoClustering', importing the 'crypto_market_data.csv' into a DataFrame, and utilizing the StandardScaler() module from scikit-learn to normalize the data from the CSV file. Following data preparation, the optimal value for 'k' was determined employing the elbow method. Ultimately, the K-means algorithm was used to cluster the cryptocurrencies using the initial scaled data, and the clusters were fine-tuned using Principal Component Analysis (PCA).

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

The comparison of the above images reveals that the Principal Component Analysis Data facilitates a lower inertia, resulting in more distinguished clusters than those achieved using the original data. This observation suggests that the PCA model is characterized by less noise and superior separability when compared to the original model.

## Tools

- Jupyter Notebook
- Python
- pandas
- NumPy
- scikit-learn
- hvPlot

## Main File

- [Jupyter Notebook](/Crypto_Clustering.ipynb)
