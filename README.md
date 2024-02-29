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

#### Findings: The impact of using fewer features to cluster the data results in data that's more concentrated between -2 to 2 PCA1 and -2 to 2 for PCA2 with Fitted predicted clusters of 3 & 0 being extremely close together. This is not the same for the graph on the left where there is both 0,1, and 3 present. Both are hyper concentrated. The cluster that is common in both is that predicted cluster of 0 is most common in both. 
