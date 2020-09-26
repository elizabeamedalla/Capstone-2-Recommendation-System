# Capstone-2-Recommendation-System

Amazon Product Recommender System

 Amazon Review Dataset available at http://deepyeti.ucsd.edu/jianmo/amazon/index.html

Introduction

Online shopping is all over the internet. All our needs are just a click away. The biggest online shopping website is Amazon. Amazon is known not only for its variety of products but also for its strong recommendation system.

In this project, I used the Surprise package. Surprise is an easy-to-use Python scikit for recommender systems. This project will show multiple different types of collaborative filtering engines, ranging from both basic neighborhood-based methods to matrix factorization methods.

Objectives
In building the recommender engine:

	• Use surprise's built-in reader class to process data to work with recommender algorithms
	• Use surprise to create and cross-validate different recommender algorithms
	• Obtain a prediction for a specific user for a particular item

In this project, I'll be working with a Amazon Reviews dataset in beauty products. This dataset contains beauty products rated by users on a scale of 1-5. In this dataset, I used user ID, product ID, rating, and product name.

Steps or Procedures

First, I run various models from Surprise. The following models were the ones used in this project.

k-NN Based Algorithms: KNNBasic, KNNWithMeans and KNNWithZScore
Matrix Factorization Based Algorithms: SVD, SVDpp and NMF
Other Collaborative Filtering Algorithms:: SlopeOne, CoClustering

Even with or without hypertuning, KNN Basic is the best model to use since this has the lowest RMSE score.  Some things to keep in mind are what type of similarities you should use. These can all have fairly substantial effects on the overall performance of the model.



Data Cleaning - https://github.com/elizabeamedalla/Capstone-2-Recommendation-System/blob/master/Data%20Cleaning.ipynb


Exploratory Data Analysis - https://github.com/elizabeamedalla/Capstone-2-Recommendation-System/blob/master/Data%20Analysis.ipynb 


Statistical Inference - https://github.com/elizabeamedalla/Capstone-2-Recommendation-System/blob/master/Statistical%20Inference.ipynb


Recommendation Engine - https://github.com/elizabeamedalla/Capstone-2-Recommendation-System/blob/master/Recommendation_Engine_Surprise.ipynb

