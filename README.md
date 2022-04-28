# COMP7118 CODE & Deliverables

Project name: Movie Recommendation System<br>
Methods used for the project: K-Means Clustering & Collaborative Filtering.<br>

Description: K-Means clustering was used to find different groups of users based on the rating scores and genres from movie dataset. Collaborative Filtering was used to find the similarity between user to an active user to predict a rating score for an unseen movie.



Software Requirenment:<br>
-Anaconda (Jupiter Notebook)<br>
-Python3

Some python libraries need to be installed before running the program
- numpy
- pandas
- matplotlib.pyplot
- mpl_toolkits.mplot3d
- seaborn
- sklearn.metrics
- math

Instruction to run the program:<br>

0. Clone the repo
1. Open Anaconda Navigator 
2. Open Jupiter Note
3. Go to the folder contains the files
4. Open comp7118.ipynb
5. Click on "Restart the kernel, then re-run the whole notebook"

Two main functions in the notebook can be found at line 103 and 137.<br>
-The function final_recommendation_system(userId) is used for getting a list of recommended movies to a user with the input is userId (int).<br>
-The function predict_rating(id_user, movieId) is used for getting a predicted rating score for an unseen movie with the input userId(int) and movieId(int).
