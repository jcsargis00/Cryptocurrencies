# Cryptocurrencies
### Requirements
* Deliverable 1: Preprocessing the Data for PCA
* Deliverable 2: Reducing Data Dimensions Using PCA
* Deliverable 3: Clustering Cryptocurrencies Using K-means
* Deliverable 4: Visualizing Cryptocurrencies Results
#### Overview
# 
This analysis created a report and visualization figures of traded cryptocurrenciesto classify similar currencies. The Accountability Accounting requested the information to offer a new investment portfolio including cyptocurrency for its customers.
#
The data was preprocessed to use an unsupervised Machine Learning model.  The model used clustering to classify cryptocurrencies. 
#
#### Tools and Techniques Used
#
* Data Preprocessing  involved selection, transformation,  and scaling of data.
* Elbow Curve was created to determine the best number of clusters needed for the algorithm to group the objects by, in our case it is 4.
* Principal Component Analysis (PCA) was used to reduce the number of features in order to optimize machine learning algorithms.
* KMeans clustering algorithm was used to grouping similar currenciess into classes.
* hvPlot and  Plotly were used to create visualizaions in 2D and 3D as scatter plots.
#
Results
#
The original dataset 1,252 rows was reduced to 1,144 cryptocurrencies when 108 currencies not currently traded were deleted. An additional 459 Nan entries were deleted, with 532 rows of data remaining.