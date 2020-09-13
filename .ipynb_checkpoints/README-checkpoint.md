# Amazon-Web-Services- Clustering Crypto

## Background

In this assignment, a report was generated using unsupervised learning on cryptocurrencies data available in the trading market. These currencies were grouped using classification.

The main tasks accomplished were:

* **Data Preprocessing**: Preparing data for dimension reduction and clustering. Creating a Pandas DateFrame by loading the csv file. Data clean-up by removing null values, keeping cryptocurrencies that are trading and with a working algorithm. Creating dummy variables for all the text features and using the StandardScaler from sklearn to standardize the data prior to using PCA and K-Means algorithms.    

* **Reducing Data Dimensions Using PCA**: Data dimensions reduced to 3 principal components using the PCA algorithm from sklearn.

* **Clustering Cryptocurrencies Using K-Means**: Predicting clusters from the cryptocurrencies data using the unsupervised learning tool KMeans algorithm from sklearn.

* **Visualizing Results**: Creating scatter plots and data tables to visualize the cryptocurrency clusters.

* **Challenge**: Deploying the results Jupyter notebook in Amazon SageMaker. Altair library was used in place of Plotly Express for data visualization.


