# MovieLens Recommendation System

A recommendation system is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item. The huge amount of data present online has led to the development of recommendation systems. These have become highly popular over the past few decades and are now used in majority of online platforms that we use. The content of such platforms varies from movies, music and books, to social media platforms and e-commerce websites. These systems are often able to gather information about a user’s choices, and use the information to improve that user’s recommendations in the future. For a system to act as a movie recommendation system, it requires basic information like movie cast, movie genre, movie plot, etc. This information helps a system categorize movies in a more efficient manner. User written movie reviews is one such example. It carries substantial amount of movie related information such as location, time period, genre, lead characters and memorable scene descriptions. 

Most of the recommendation systems can be classified into either User based collaborative filtering systems or Item based collaborative filtering systems. In User-Based collaborative filtering, a target users' choices are compared with other users in the database to identify a group of “similar minded” people. Once identified, highly rated content from the group is then recommended to the target user. Item-based collaborative filtering examines each item on the target users' list of rated items and finds other items in the choice set that seems similar to the item. Such systems would be useful when a group has to take a decision from a large set of possibilities and the decision affects all the members of the group. The system recommends the same movies to users with similar demographic features. 

Since each user is different, this approach is considered to be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience. Both research and applications of recommender systems have traditionally focused on providing recommendations to single users; the idea can however easily be extended to recommendations to groups of people. 

For this project we will make a movie recommendation system using the 10M MovieLens dataset and use soft computing techniques to develop this system. The idea here is to develop a model which can effectively predict movie recommendations for a given user. In the algorithm, the prevalence can be suppressed using some clever mathematical tricks. The metric used to evaluate recommendation systems is the Root Mean Square Error, or RMSE. RMSE is a measure of accuracy and one of the most used measure of the differences between values predicted by a model and the values observed.
