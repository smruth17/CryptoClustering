# CryptoClustering
Module 19

The Module 19 homework assignment consists of using Python and Unsupervised learning to predict if cryptocurrencies are affected by 24 hour or 7 day price changes. The first step was to read in the csv and load into a DataFrame. Then I reviewed and plotted the data. Due to some larger variance in some of the columns, I used the scaler. The next step was to run the scaled data through K means and Clustering. After this, the scaled data was run through PCA before running the PCA data through K means and Clustering. Both outcomes identified similar results, however the data run through PCA was clearer and more identifiable since the data was simplified. The trade off with using PCA is that you may lose some information in the process. 
