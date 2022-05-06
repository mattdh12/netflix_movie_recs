# netflix_movie_recs

The goal of this module is to identify similar movies based on movie characteristics for Netflix. This will be a truly unsupervised learning problem, as there is no target variable. As a result, there is not a known number of clusters ahead of time, so this module will have to explore the appropiate number of clusters.

The data was pulled from https://www.kaggle.com/shivamb/netflix-shows

The movies ended up being clustered where all their genres and subgenres were identical. This actually worked out quite well. At one point in this module, it was attempted to include more features in the modeling dataset, such as including the director or the cast. This ended up creating more features than actual movies, which would have made clustering ineffective. That idea was then scrapped and it was decided to only keep genres. If a substantial amount of movies are added to Netflix, then using more features may be feasible. For the number of current movies listed, using only genres works fine.

As it stands now, there are no real future plans for this project. I may end up using it as a playground to test out unused clustering methods though.
