# module_13_challenge
# Ne 
The goal for this financial notebook is to make a comprehensive way to segment our data. We do this by creating two ways to find our clusters one by the elbow curve and the other by using PCA method.
-------------------------------------------------------------------------------------------------------------------------

# Technologies Used
We used Jupyter notebook, sklearn, pandas, hvplot, PCA, KMeans and StandarScaler.  
-------------------------------------------------------------------------------------------------------------------------

# Installation
We will need Pandas and import sklearn which gives the cluster building blocks.
-------------------------------------------------------------------------------------------------------------------------

# Example
For this notebook we grab a csv file convert it to a DataFrame. Once converted, we use the data inside to form our clusters first we grab the elbow curve to find the best KMeans cluster and then graph using hvplot. After we can go above and beyond using PCA to find the optimal cluster value, this can differ from the previous cluster guess we used. If it is different, that is okay due to the computer calculating it and we also some accuarcy. After both are graphed we can check to see what difference the clusters is.
-------------------------------------------------------------------------------------------------------------------------