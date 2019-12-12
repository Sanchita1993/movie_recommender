Implementation of a recommender system
Basically 3 types of algorithms are used to implement recommender system
1.Based on Popularity 2. Based on Content 3. Collaborative filtering
In this system I have implemented recommender sytem based on Content.
Content based system is based on the similarity of items.It is based on the past experience of whatever user have searched for or whateve you have watched
or whatever user have bought, the system finds the most similar items related to those items and then recommend user next time.
Dataset used is downloaded from IMDB
Important libraries of Python used are pandas, skikit-learn
To count number of similar words in a given text a class called countVectorizer is used.
Similarity between items are calculated with  cosine_similarity method.

