# Movie Recommendation
A simple movie recommendation project based on Tensorflow (v1.x), Collaborative Filtering and Matrix Factorization.

The basic idea is that for each "user", give every movie in the dataset a score based on the user's previous ratings on movies. Two tables are used, 'movies' have all movies' names and movie id; 'ratings' have all users' ratings. A more detailed and theoretical explanation can be found [here](https://towardsdatascience.com/recommendation-system-matrix-factorization-d61978660b4b).

To use Tensorboard to visualize the loss while training the model, open up the terminal, go to the folder where 'movie_tensorboard' is saved and run `tensorboard --logdir=./` Then go to 127.0.0.1:6006.

Datasets can be downloaded from https://grouplens.org/datasets/movielens/.
