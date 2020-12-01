# Book-Reco- Matrix-Factorization-using-SVD-ALS-and-Deep-Learning
The purpose of this repository is to illustrate multiple ways of doing matrix factorization.

The purpose of this notebook is to illustrate one of the most widely used ways of generating recommendations using low rank matrix factorization using three alternate methods of doing it.

Singular Value Decomposition (SVD)
Alternating Least Squares
Deep Learning (the example uses TF2.x, but one can use Pytorch to generate similar results)
Matrix Factorization involves decomposing a large matrix (usally an User-Item matrix in the context of item personalization) into two smaller latent factor matrices. The dot product of these two matrices approximates the already known ratings and at the same time is able to produce ratings for user-item combinations which had no values in the original matrix

The original source data for this repository can be found on Kaggle public datasets:  https://www.kaggle.com/bahramjannesarr/goodreads-book-datasets-10m

Note: results may vary in each run as I have not seeded everything, but core essence of the notebook remains the same.
