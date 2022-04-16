# Event-Recommendation-System
Recommendation Engine
Building a Event Recommendation Engine using a dataset made by VIT students themselves
We will be using an original dataset made by the students of VIT. This dataset contains 18000 ratings across 2000 events for 119 users.

We are going to build a recommendation engine which will suggest events for a user which he hasn't attended yet based on the events which he has already rated. We will be using k-nearest neighbour algorithm which we will implement from scratch.

Mounted at /content/drive
event file contains information like event id, title, domains of event and ratings file contains data like user id, event id, rating and timestamp in which each line after header row represents one rating of one event by one user.
Let us see the number of users and number of movies in our dataset
how many events were rated by each user and the number of users rated each event
Function to find top N favourite events of a user
Lets build recommendation engine now

We will use a neighbour based collaborative filtering model.
The idea is to use k-nearest neighbour algorithm to find neighbours of a user
We will use their ratings to predict ratings of a movie not already rated by a current user.
We will represent movies watched by a user in a vector - the vector will have values for all the movies in our dataset. If a user hasn't rated a movie, it would be represented as NaN.
Now, we will find the similarity between 2 users by using correlation
We will now use the similarity function to find the nearest neighbour of a current user

Predicting top N recommendations for a current user


finding out the recommendations for a user
User's favorite attended events are :  ['Regular Control', 'Compute Speed', 'Virus Room', 'Art Coding', 'Job Study'] 
User's top recommendations are:  ['Decoding Running', 'Domain Story', 'Lesson Speed']
Conclusion
We have built a event recommendation engine using k-nearest neighbour algorithm implemented from scratch.
