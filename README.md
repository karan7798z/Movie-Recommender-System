# Movie-Recommender-System
This is a movie recommendation system based on Content-Based and Collaborative-Filtering approaches for recommendations

In this project I have used 2 widely adopted approaches of building recommender systems, to recommend movies to users.

The 2 widely used approaches are -

### 1. Content Based Recommenders -
In this, recommendations are provided to users on basis of their profile, which revolves around their preferences and tastes.

I have broadly used 3 different types of metrics to recommend a movie using this methodology - 

* Recommendations on basis of genres
* Recommendations on basis of movie plot description
* Recommendations on basis of credits, genres and keywords

A sample recommendation list for an input movie - 'The Dark Knight', using the 3rd type of content-based recommendation engine, returned following output - 

* The Dark Knight Rises
* Batman Begins
* The Prestige
* Hitman
* Kidnapping Mr. Heineken
* The Outsider
* Tell
* Kill Dil
* Boy Wonder
* House of the Rising Sun

### 2. Collaborative Filtering -
In this, user is matched to similar users (based on preferences), and then items that the similar users have liked are recommended against the provided input. Basically in this, users are matched and there is no need to extract information from the recommended item unlike content-based filters.
