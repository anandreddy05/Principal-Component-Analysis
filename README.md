# Principal-Component-Analysis
Principal Component Analysis using IRIS dataset
# Applying PCA
In this dataset we have 4 columns so the dimensionality is 4
we reduce 4D to 1D
## Steps:-
- Apply MinMaxScaler or StandardScaler -> Normalizing Data
- Create Covariance Matrix (cov())
- Calculate Eigen value and Eigen vector (eig())
- Extract only the Eigen value that is maximum with its corresponding eigen vectoe
- Project the data on to that Eigen Vector (dot())
- The dimensionality is reduced
