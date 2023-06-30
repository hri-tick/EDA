# EDA
STEPS INVOLVED IN NOTEBOOK
WE PERFORM AN EXPLORATORY ANALYSIS OF UNKNOWN TIMESERIES DATASET
1)Look at data structure,time-series - r1 to r12, correlation between features, created data functions, normalization of time-series data - 

![feature_description](https://github.com/hri-tick/EDA/assets/138192141/cb352101-66b3-4254-9f52-c740f7fd03ec)


2)Visualize the time-series to gain insights into its pattern,trends over hourly,daily,monthly,seasonal timestamp and some other visualizations

![r1_daily](https://github.com/hri-tick/EDA/assets/138192141/ad8cb81b-deb6-4568-903e-bc601d58e649)
![r1_hourly](https://github.com/hri-tick/EDA/assets/138192141/11bb0422-adb0-4ea1-8fa9-472d71fec137)
![r1_monthly](https://github.com/hri-tick/EDA/assets/138192141/6411c47e-3dff-4af7-aa3b-15513cc059ac)
![r1_seasonal](https://github.com/hri-tick/EDA/assets/138192141/428a9321-b22c-43f6-b9c3-2a94dc7f5b4d)


3)using DTW method as it is a technique used to compare and measure the similarity between two time series data sequences on r1 to r12 = giving 66 combinations

![dtw_distances_for_seasonal](https://github.com/hri-tick/EDA/assets/138192141/f8e9be64-a6dc-4539-a856-ad5b6a90313a)

DTW distances calculated on timeseries data over hourly,daily,monthly,seasonal timestamp

4)Using elbow method to determine no. of clusters for dtw_distances

![elbow_method_kmeans](https://github.com/hri-tick/EDA/assets/138192141/87b10b44-2953-4e22-ac8e-61d3694a0f84)


5)Cluster visualization

![kmeans_dtw_seasonal](https://github.com/hri-tick/EDA/assets/138192141/c26ec5c4-6cc1-488c-9137-1bca4add16a8)

6)Kmeans Clustering on r1 to r12, visualization of clusters

![kmeans_elbow2](https://github.com/hri-tick/EDA/assets/138192141/a9e441f1-3f47-49a0-b864-dd2833708a10)
![cluster_r12](https://github.com/hri-tick/EDA/assets/138192141/5e170b0b-3f38-4d4f-b5e5-3b3bf81fddb1)


7)Analysis of Kmeans CLustering with respect to other features of Dataset
here is with temp and humididy

![temp_cluster](https://github.com/hri-tick/EDA/assets/138192141/0ded6238-b719-4d5a-86df-b6da79f07fe6)
![humidity_cluster](https://github.com/hri-tick/EDA/assets/138192141/bbb67e30-5ec2-4219-acc9-a66ecc981271)



You can find the relevant code in the notebook linked to the repo. Feel free to explore more 
