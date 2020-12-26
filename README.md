# Machine Learning in Films
Some data analyses, visualizations, and predictive models related to the Movies and Films area using data obtained from IMDB (and others) databases.

## Notebooks:
### Word2Vec in non-NLP context
In this notebook I use Word2Vec for encoding films' cast and crew into 100-length vectors. The algorithm uses the other members of a movie's cast and crew as context through which it learns the numerical representation of a certain actor/actress. Later I use these novel features as predictors in a Logistic Regression model for estimating the probability of a movie being among the Top 1% in terms of IMDB votes.
