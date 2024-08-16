# CryptoClustering

Module 19 Challenge

In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

First I prepared the data for clustering analysis by normalizing the data and created a new DF containing that data.  Next, created the elbow curves to find the optimal cluster value as well as plotted on a scatter plot both the original scaled data.  Once the original scale data creation was completed, i performed similar analysis using data with fewer features/dimensions calculated from Principal Component Analysis (PCA).

Finally, I compared clustering results from the original scaled data and the PCA data to evaluated how the reduction in features affected cluster separation and quality.

It appears that using fewer features allowed for tighter clusters (Eblow Curve 2) as shown via the lower inertia value. Along with that, when looking at the scatter plots, there is less overlap between the clusters themselves and are shown being more defined (PCA1 v. PCA2). Overall, using the PCA data (less features) has had a positive impact allowing us to more accurate and impactful clustering.