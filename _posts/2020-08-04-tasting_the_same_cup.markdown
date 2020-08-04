---
layout: post
title:      "Tasting the Same Cup"
date:       2020-08-04 14:35:16 +0000
permalink:  tasting_the_same_cup
---


The complete blog can be found in the url below:
https://medium.com/@khuloodnasher72/tasting-the-same-cup-2347bfbdb960


There is a proverb in Arabic culture that says ’Taste the same cup’ meaning face the same experience that was faced previously by others. The idea of tasting the same cup has been adopted to the recommendation system that applies collaborative filters. It’s applications can be noticed in recommending new media to the users of Netflix and Youtube or new products to the users of Amazon, or recommending new friends on facebook.
Because of the collaborative filters of the recommendation system in Netflix, the new user will try the same taste of old customers and watch movies that had been watched previously by old users.
Collaborative filters are based on the fact that the system doesn’t know what features they have to do their recommendation for their new users .
When a new movie is uploaded, we don’t know the features of this movie, for example its genre. The old users have experience with old movies that they watched in the past and they had rated them. Some of the old users love romantic movies so they rated romantic movies 5 , but they don’t like action movies so they rated action movies 0. Their rating vector will look like as follows:
Image for post
The first row is the bias and the second row is their rate of romantic movies with 5 and the third row is their rate of an action movie with zero .
While there are other old users who love action movies but they don’t like romantic movies. They will weigh the action movies with 5 and will weigh the romantic movie with zero. Their rating vector looks as follows
Image for post
The first row is the bias, The second row is the weight of zero that was given for romantic movies. The third row is the rating of 5 given by this old customer to an action movie.
Since I know the vector of coefficients of old users who are passionate for romantic movies, and I know the vector of coefficients of the old users who are passionate for action movies, when a new movie is uploaded to netflix and we don’t know what feature it is, this means I don’t know what x is this movie, but this movie was watched by old customers who I know their vector of weights. If the new movie was rated by the old romantic user with 5, I can predict that the feature of the new movie is romantic, and the vector of the new movie will look like this:
Image for post
So the new movie feature will be tuned to be romantic. Where the first 1 is for the bias and the second 1 is for the romantic movie and the zero is for the action feature.
But if a new movie was watched by old users who love action movies and they rated this new movie with 5, The new movie will be tuned as an action movie and the vector of this new movie will look like this:
Image for post
Where the first 1 is for the bias and the 0 in the second row is for the romantic feature and the third row is for the action feature.
