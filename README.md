# Recommendations Engine for IBM Watson


# Introduction:
- This project is part of the Udacity Data Science NanoDegree Program. 
- Here, we will be putting skills of building recommendation engine to use on real data from the IBM Watson Studio platform.
- For this project you will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.


# Tasks:

## I. Exploratory Data Analysis:

- Before making recommendations of any kind, we will need to explore the data you are working with for the project. We will dive in to see what we can find. 
- There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. We will use this space to explore, before we dive into the details of our recommendation system in the later sections.



## II. Rank Based Recommendations:

- To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. 
- Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).



## III. User-User Based Collaborative Filtering

- In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. 
- These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. We will implement this next.



## IV. Matrix Factorization

- Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. 
- Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.
