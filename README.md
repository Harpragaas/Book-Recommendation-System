# Book-Recommendation-System

A Book Recommendation System which recommends the user a selection of books based on their interests.

Here, I used Collaborative Based Filtering Method to build a book recommendation system.


## Model Used : Nearesr Neighbor Based Recommendation 

The nearest neighbor model used is similiar to K-nearest neighbor which is used for clustering based on euclidean distance.

To train the Nearest Neighbors model, I have created a sparse matrix taking ratings of each Book by each User individually. This matrix is used to train Nearest Neighbors model and then to find n nearest neighbors using the Cosine Similarity.

