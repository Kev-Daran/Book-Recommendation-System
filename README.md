# Mini Project
# Book-Recommendation-System
A recommendation system is one of the top applications of data science. Every consumer Internet company requires a recommendation system like Netflix, Youtube, a news feed, etc. What you want to show out of a huge range of items is a recommendation system.
A recommendation engine is a class of machine learning which offers relevant suggestions to the customer.  Before the recommendation system, the major tendency to buy was to take a suggestion from friends. But Now Google knows what news you will read, Youtube knows what type of videos you will watch based on your search history, watch history, or purchase history.

A recommendation system helps an organization to create loyal customers and build trust by them desired products and services for which they came on your site. The recommendation system today are so powerful that they can handle the new customer too who has visited the site for the first time. 

A book recommendation system is a type of recommendation system where we have to recommend similar books to the reader based on his interest. The books recommendation system is used by online websites which provide ebooks like google play books, open library, good Read’s, etc.

We have designed various ML models for a Book Recommendation System using Python and Google Colab.
## Algorithm 1-Using Demographic and Collaborative Filtering
->The first ML model uses demographic filtering to give the top 20 highest rated books and authors.<br/>
->It uses collaborative filtering to predict the books to be recommended to the user.<br/>
->Collaborative based filtering recommender systems are based on past interactions of users and target items.  In simple words here, we try to search for the look-alike customers and offer products based on what his or her lookalike has chosen. Let us understand with an example. X and Y are two similar users and X user has watched A, B, and C movie. And Y user has watched B, C, and D movie then we will recommend A movie to Y user and D movie to X user.<br/>
->In this model, we use the surprise library in Python. Surprise stands for Simple Python Recommendation System Engine.We import Reader,Dataset and SVD.<br/>
->This model uses the famous SVD algorithm. An empty list is declared and the data extracted using Dataset is iterated over all algorithms in SVD to be cross-validated.<br/>
->It then uses the df data to find the books read by the users and their rating and recommends books accordingly.<br/>
