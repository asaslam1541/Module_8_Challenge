# Module_8_Challenge
## Steps
- Through Path imported the dataset into the dataframe; df_market_data.
- By using hvplot.line command view the cryptocurrency in the dataframe.
- Prior to running K-Means algo, prepared the data through StandardScaler().fit_transform().
- Created a new dataframe with the processed data called; df_market_data_scaled.
- Created a new dataframe to find the optimum value of k and inertia. To do so, ran through a loop the value of k.
- Through hvplot.line created a graph and included the graph in a separate variable so a composite graph can be created later.
- Initialised the model by using the original data, fitted it through the original data, predicted the clusters of the cryptocurrency.
- Through hvplot.scatter visualised the results and saved them under a separate variable called original_scatter_graph.
- Through Principal Component Analysis reduced the features to three, and included the results of the dataframe in the dataframe called pca_data_df.
- Calculated the variance explained ratio, which was approx 0.9
- Calculated the value of k and inertia again and saved the data in the dataframe called pca_elbow_df and displayed it in the graph called pca_elbow_curve
- Initialised the model by using the PCA data, fitted it through the PCA data, predicted the clusters of the cryptocurrency.
