# CryptoClustering
MSU Data Analytics BootCamp Module 19 Challenge

Code file name: 'Crypto_Clustering.ipynp' located in the root repository directory

This Jupyter notebook performs the following functions:

The code inputs a CSV file containing data consisting of numerous cryptocurrency brands and their % price changes over different periods of time. The goal is to use an unsupervised machine learning algorithm to statistically cluster different crypto brands based on these price changes. This is done using both raw (scaled) data and the same dataset reduced in dimensionality using principal component analysis. The CSV input file is located in the 'Resources' subdirectory of the root repository directory. After inputting the CSV, several functions are performed:

 1. The raw cryptocurrency data is scaled for use in an unsupervised machine learning k-means clustering algorithm provided by the scikit-learn Python library
 2. The inertia of the scaled data is calculated for clusters numbering 1-11
 3. An elbow plot of inertia vs. clusters is created to determine the optimal k number for the k-means clustering algorithm
 4. Using the optimal k as indicated by our elbow plot, the k-means clustering algorithm is performed on the scaled data
 5. Individual cryptocurrencies are assigned to a predicted cluster and then charted on a 2D scatter plot
 6. The scaled data is then reduced in dimensionality using principal component analysis
 7. Steps 2-5 are performed again for the PCA reduced data

*Code sourcing statement*
-----------------------

I did use a natural language description of some desired code functions entered into ChatGPT 3.5 to help build the code structure. I did copy pieces of that code to be more efficient, but I tailored it to fit all the desired functions of this particular project. I did not directly copy and paste any of this code from the internet otherwise (e.g., from StackExchange or any other webpage). I did not seek any assistance or use code written by my peers or instructors for this challenge.

End of code sourcing statement.

 ----------------------
