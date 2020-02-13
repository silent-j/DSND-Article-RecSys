# DSND-Article-RecSys
An analysis of user interactions on IBM's Watson Studio platform. The goal of this project is to experiment with different recommendation system methods and identify the strength and weaknesses of each. 

# Installation
The project requires Python 3.x or higher. The following libraries are used:

  - Pandas
  - Numpy
  - Scikit-Learn
  - Matplotlib
  - TQDM

# Data
user-item-interactions.csv: dataset user interactions.

articles_community.csv: dataset containing article descriptions.

# Summary

I. Exploratory Data Analysis

II. Rank Based Recommendations:

Recommendations of articles are provided based on total user interactions.

III. User-User Based Collaborative Filtering:

User-article interaction data is used to generate recommendations. Recommended articles are sorted by similarity, and by the total number of user interactions.

IV. Content Based Recommendations (Extra Credit): 

In this section I create a simple class which determines the Cosine Similarities of article titles and provides user recommendations based on previously read articles. 

V. Matrix Factorization:

Singular Value Decomposition (SVD) is applied to training and testing data subsets to predict user interactions with articles.

# Ackowledgements

https://www.udacity.com/ has provided the structure of the jupyter notebook and the project_test.py file for verifying most solutions to each section. IBM has provided the data files.
