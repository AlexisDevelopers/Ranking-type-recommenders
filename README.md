This project is a movie recommender based on a rating system. It uses a dataset of movies that contains information such as title, genre, number of votes, and average rating on IMDb.

The goal of this project is to recommend movies that have a high average rating and have received a large number of votes. To do this, first the films that have received the fewest votes are filtered and a cut-off point is established to select the 10% of the films with the highest number of votes.

Next, the average rating of all movies in the dataset is calculated, and a function is created to calculate each movie's weighted rating based on its number of votes and its average rating.

This function applies to the entire data set and is stored in the "score" column. Movies are ordered based on their rating, and the top 25 movies are listed along with their title, number of votes, average rating, and genre.

To run the project, you need to mount the Google drive and load the movie dataset in CSV format to the specified path.