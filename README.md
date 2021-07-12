# Cryptocurrencies
Machine Learning (Supervised and Unsupervised Learning)

# Project Overview
The objective of this project was to create an analysis for clients at an investment bank who are preparing to invest in the cryptocurrenicy market using Unsupervised machine learning to process data, cluster, reduce dimensions and principal components by applying Principal Component Analysis, or PCA. The analysis entailed creating a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Scope 
The cryptocurrency dataset was retrieved from CryptoCompare web site. Since the data used for this project was not ideal, it needed to be processed to fit the machine learning models. The analysis employed unsupervised learning was used to group or cluster the cryptocurrencies together because there was no knonwn output. K Means model, a clustering algorithm was performed to identify the number of clusters and best value for k Using the Elbow Curve. The findings from the analysis were visualized using Plotly Express and hvplot. Scatter plots were generated to visualize the distinct groups that correspond to the three principal components created, and table with all the currently tradable cryptocurrencies using the hvplot.table() function.

Dataset source: https://min-api.cryptocompare.com/data/all/coinlist


## Technologies
Jupyter Notebook, Python, Pandas DataFrame, Machine Learning models, and multiple machine learning libraries were imported.

# Results

kmeans_unsupervised_learning.png![kmeans_unsupervised_learning](https://user-images.githubusercontent.com/80140082/125209098-5f0c5380-e24b-11eb-8580-f97b7e0f58c6.png)



plot_3d.png![plot_3d](https://user-images.githubusercontent.com/80140082/125292861-b952f600-e2d7-11eb-8611-ca2102ff6205.png)



tradeable_currencies.png![tradeable_currencies](https://user-images.githubusercontent.com/80140082/125209214-3173da00-e24c-11eb-8181-e82993be3cfc.png)


scatter_plot.png![scatter_plot](https://user-images.githubusercontent.com/80140082/125292270-274aed80-e2d7-11eb-9e95-83720242e44f.png)


