# EDA
STEPS INVOLVED IN NOTEBOOK
WE PERFORM AN EXPLORATORY ANALYSIS OF UNKNOWN TIMESERIES DATASET
Look at data structure,time-series - r1 to r12, correlation between features, created data functions, normalization of time-series data - 

![feature_description](https://github.com/hri-tick/EDA/assets/138192141/cb352101-66b3-4254-9f52-c740f7fd03ec)


Visualize the time-series to gain insights into its pattern,trends over hourly,daily,monthly,seasonal timestamp and some other visualizations in notebook to understand better about data.

![r1_daily](https://github.com/hri-tick/EDA/assets/138192141/ad8cb81b-deb6-4568-903e-bc601d58e649)
![r1_hourly](https://github.com/hri-tick/EDA/assets/138192141/11bb0422-adb0-4ea1-8fa9-472d71fec137)
![r1_monthly](https://github.com/hri-tick/EDA/assets/138192141/6411c47e-3dff-4af7-aa3b-15513cc059ac)
![r1_seasonal](https://github.com/hri-tick/EDA/assets/138192141/428a9321-b22c-43f6-b9c3-2a94dc7f5b4d)

Using Elbow method to determine no. of clusters for Timseries KMeans Method
![elbow_method](https://github.com/hri-tick/EDA/assets/138192141/facb4172-cc70-4511-ad4f-6da32a19c0c8)


Timeseries KMeans algorithm using 2 different metrics - DTW and Euclidean on monthly,seasonal,daily,hourly data

1 - r1-r12 monthly on one plot


![r1-r12_same_plot](https://github.com/hri-tick/EDA/assets/138192141/df59301b-8f54-47a3-bfee-bd5c55ac61d1)

2 - Timeseries KMeans by DTW metric for Montly Data


![timeseries_kmeans_monthly](https://github.com/hri-tick/EDA/assets/138192141/b42a01dd-d561-4d7f-9099-e84a87a84e19)

3 - Timeseries KMeans by Euclidean Metric for Monthly Data


![timeseries_kmeans_monthly_euclidian](https://github.com/hri-tick/EDA/assets/138192141/fb7b6d14-40a6-4ec5-8cea-331d278f540c)


4 - on Seasonal Data - DTW

![timeseries_kmeans_seasonal](https://github.com/hri-tick/EDA/assets/138192141/7bb1177d-5c65-4a51-b815-37d36a5104a5)


5 - on Daily Data -DTW


![daily_kmeans](https://github.com/hri-tick/EDA/assets/138192141/17c75255-2c7b-459b-b644-cc29ed93fc05)


Other Cluster Plots, thier Silhouette Score, and details is in the notebook

Conclusion - *DTW Timeseries KMeans Clustering gives more Silhoutte Score on this dataset rather than Euclidean Timeseries KMeans Clustering*

You can find the relevant code in the notebook linked to the repo. Feel free to explore more 
