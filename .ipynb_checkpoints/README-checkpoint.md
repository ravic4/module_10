# module _ 10 : Clusters: 
### This code was done through the help of Shah, Pablo, also spoke to Kayla about the assignemnt. Furthermore, I also reference homework assignments and other inclass homework 
### Steps for the code: 
1. Called in my original dataframe which consisted of % change of crypto prices
2. Plotted my dataframe to se what's inside 
3. Scaled my dataframe and set "coin_id" as my index 
4. Fit my df_market_data (dataframe) to inertia (my first K-value) 
5. Plotted my elbow curve
6. Clustered cryptocurrencies using scaled data 
7. fit_transformed my df_market data
8. Re-fit my data using df_pca_market_concat
9. Plotted elbow curve 
10. Refit my df_pca_market_concat 
11. Plotted my PCA data. 

#### Findings:The impact of using fewer features to cluster the data results is that predicted clusters becomes less concentrated from 1 to being split between 0 and 3 (see graph on the right). By using fewer features, we can concentrate into a more specific set of clusters (graph on the right) vs. on the left which is 0 & 1. Therefore, using lesser features to cluster the data is more beneficial to observe patterns and trends. 
