# IMDB_movie_predictions

#### Question of Interest
Is it possible to predict the popularity of a movie prior to its release based on certain characteristics of the movie, to be specific are variables such as movie genre, MPAA rating, run length, etc. good predictors of a popular movie?

#### Dataset
The [dataset](https://stat.duke.edu/~mc301/data/movies.Rdata) contains information about movies in Rotten Tomatoes and IMDB. There are 651 randomly sampled movies produced and released before 2016. There are 32 available variables. The study can be generalized to movies produced and released before 2016.

#### The Predictive Model
- Data Modeling: I used a backward elimination method of stepwise regression and was left with a initial model with fewer predictors. 
- Model Diagnostics: I looked at a Residual vs Fitted plot, histogram of residuals, and QQ-plot to determine that the final model followed all assumptions of linear regression. 
- Testing the Predictions: I used the model to predict the scores of the movies Dirty Grandpa and Deadpool with Dirty Grandpa being almost spot on, but Deadpool being even outside its 95% confidence interval.  

#### Conclusion
It definitely is possible to roughly predict the popularity of a movie given enough movie data; however, in my final multivariable linear regression model, there was definitely improvements that could have been made such as maybe creating separate models for each movie genre, identifying sequels, or searching for keywords in the movie title and description. 

#### What I learned
I was able to practice exploratory data analysis, use of external libraries(ggplot2 and dplyr), visualization techniques (pairwize plots and histograms) and the general intuition about the dataset from learning more about the variables and distributions. The project definitely had me looking through multiple online sources to find specific tests I needed and the interpretation thorugh those results. 

