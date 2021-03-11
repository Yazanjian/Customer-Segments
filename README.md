# Identify Customer-Segments
This project is to identify possible customers for a company using real data. 
This is also the third project in Into to Machine Learning with Pytorch Nanodegree from Udacity. 

## Project Goal 
The goal of this project is to study real dataset for a company and extract information that may be used for marketing or product improvement.
The project is built by using unsupervised ML techniques, specifically clustering using k-means algorithm. 

## Files Describtion
There are two files in this project: the notebook file and a web page. Both have the code and results. 


## Project main steps
The project contains Data Preprocessing, Feature Transformation and Clustering. 
* In Data Preprocessin, we assessed missing data in cloumns and rows as well as apply feature selecetion and feature engineering on some of the attributes. 
* In Feature Transformation step, feature scaling as well as PCA was applied on the data. 
* In the last step, Clustering, k-means clustering model with k=26 was built. A comparison between two datsets (General population and customers) was done to extract useful information. 

## Results 
After building the model and use it to predict the clusters for each customer, we noticed the following:
* It is important to target people in clusters 2,8, 14 and 21 (Overrepresented).
* Also it is important to notice the features that corrolates with princibal component in consumers. For example, GEBAEUDETYP_RASTER ,MIN_GEBAEUDEJAHR in cluster 21.
* Some underrepresented clusters are: 3, 6,9 and 18 which the company doesn't need to target them at this level. 

## Licensing, Authors, Acknowledgements
Credits given to Udacity for providing the initial formatting document for this project. The data was provided by Udacity partners at Bertelsmann Arvato Analytics.
