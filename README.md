# Unsupervised-Learning-Challenge

In this activity, myopia data was provided and modeled in order to determine if a there is a better way to predict mypopia in patients. In step 1, the data was loaded into a Jupyter notebook and cleaned using the following:
    1. Drop the MYOPIC column due to the bias it would provide to the model.
    2. Determine if any null values or duplicate values were present. None were detected for this dataset.
    3. Standardize the data using StandardScaler from sklearn. This is done so as the large values in some columns do not not influence the outcome more          compared to columns with smaller values.

In step 2, a dimensionality reduction was performed with PCA at 90% of the explained variance. Using this, t-SNE was performed to further reduce the dataset dimensions. t-SNE was then plotted in order to visually see if any clusters were formed. As seen in the Jupyter notebook, there were no defined clusters.

In step 3, a second cluster analysis was performed using K-means. With this analysis, an elbow curve was created, and a small joint was seen at 3 clusters indicating that patients could be clustered. 
