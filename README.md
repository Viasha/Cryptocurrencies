# Cryptocurrencies
## Overview
The purpose of this project is to create a report of cryptocurrencies with a vizualization so the currencies can be grouped together to create a new classification system. The data provided from CryptoCompare supplied me with current trading data needed to process the unsupervised Machine Learning model to complete this analysis. During this analysis I expressed my skills aquired in Data Preprocessing, Elbow Curve plots, PCA, KMeans Algorithms and hvPLot vizualizations.

## Results
The original data needed some preprocessing to eliminate null values and cryptocurrencies that were not currently traded. The final results yielded cryptocurrencies with a total number of mined coins greater than 0. 

![clustered_hvplot](https://user-images.githubusercontent.com/93167609/160226911-25ca581a-251e-4047-9e19-26115d463b42.png)

The Elbow Curve generated a slope that identifies the number of clustered recognized by the KMeans algorithm.

![Elbow_curve](https://user-images.githubusercontent.com/93167609/160226951-6ec4eda4-289b-4df5-80d2-4b323225ac23.png)


The 4 clusters on shown in 3D scatter plot vizualization

![3D_hvplot](https://user-images.githubusercontent.com/93167609/160226961-06fa2096-4623-4fe9-bd96-68f8ad2dd69c.png)
