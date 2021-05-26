# Recomander-System-project
Here I examine the use of colibrating filtering algorithms on the movie lens data. 

Main code file - recomandr_system_movie_les.ipynb

In this project i examine three basic algorithms of collabirating filtering : cosine similartiy, pearson similarty and matrix factorixation vis SVD algorithms. 
After examination it was found that the matrix factorixation give the best result via f1 score and RMSE wise. 

Then basing on user similarties, for each user, was created a 10 movie recomandation list and an estimation of the rating. 

In addition, i examine another use case - regarding the sutiation that a user is viewing some movie and we want to give him 
recomandation basing on movies that are similar to this movie. 
For this , i have udes knn - cosine similarty algorithm, and for the user "i", for the movie "j", the top 5 nearest neighbhors to the movie "j", were taken from the recomandation list. 

