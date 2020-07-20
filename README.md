# recommendation_system

OVERVIEW:

This repository is a collection of  movie recommendation based on both collaborative and content based filtering . 
In this project, we will implement and analyze the performance of collaborative ﬁltering methodsof type:
  Neighborhood-based collaborative ﬁltering
  
  Neighborhood-based collaborative ﬁltering

The basic idea in neighborhood-based methods is to use either user-user similarity or item-item similarity to make predictions from a ratings matrix. There are two basic principles used in neighborhood-based models:

    User-based models: Similar users have similar ratings on the same item. Therefore, if John and Molly have rated movies in a similar way in the past, then one can use John’s observed ratings on the movie Terminator to predict Molly’s rating on this movie.
    Item-based models: Similar items are rated in a similar way by the same user. Therefore, John’s ratings on similar science ﬁction movies like Alien and Predator can be used to predict his rating on Terminator.
    In this project, we will only implement item-based collaborative ﬁltering (implementation of user-based collaborative ﬁltering is very similar).


Collaborative:
ITEM_BASED filtering is used here:
     models that help recommend movie suggestions based on other users' ratings, as well as determine how well the recommender engines perform.
     
Content :
      models that help recommend movie suggestions based on genere and find similar movies.
      
Dataset:
 The data used is from the MovieLens datasets (https://grouplens.org/datasets/movielens/)
 
Statistical Methods and Models Used:

Pearson's r
Cosine similarity
Correlation matrix


Pearson-correlation coeﬃcient

Pearson-correlation coeﬃcient between users u and v, denoted by Pearson(u,v), captures the similarity between the rating vectors of users u and v. Before stating the formula for computing Pearson(u,v), let’s ﬁrst introduce some notation:

Iu : Set of item indices for which ratings have been speciﬁed by user u
Iv : Set of item indices for which ratings have been speciﬁed by user v
µu: Mean rating for user u computed using her speciﬁed ratings
ruk: Rating of user u for item k


k-Nearest neighborhood (k-NN)

Having deﬁned similarity metric between users, now we are ready to deﬁne neighborhood of users. k-Nearest neighbor of user u, denoted by Pu, is the set of k users with the highest Pearson-correlation coeﬃcient with user u

Library Used:
Pandas
Sklearn
numpy

