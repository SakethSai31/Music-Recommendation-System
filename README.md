# Music-Recommendation-System


## Problem Statement

Recommender systems have become extremely popular in multiple areas such as movies, books, music, news,etc. Music Recommendation System has seen a surge in the usage of the users opting for online music streaming services. MRS research continues to face significant obstacles even if today's MRSs significantly assist consumers in finding interesting music in these vast archives. Developing, implementing, and evaluating recommendation techniques that utilize knowledge beyond a basic metric and parameter to suggest a recommendation is challenging. In this project, we examine the state of the art recommendation systems for overcoming these difficulties,  we will outline potential future directions and thoughts.


## Architecture Diagram

![Architecture_Final](https://github.com/SakethSai31/Music-Recommendation-System/blob/main/Data/Spotify%20algo.jpeg)


## Abstract

With the help of Spotify dataset, we are performing analysis on the given metrics/ parameters of the song such as the year in which the song was released, the liveness and danceability score of each song, and popularity of the song. Post analysis we can form various clusters of multiple songs by leveraging clustering algorithms such as k-means clustering. We Aim to build a Music recommendation system with the use of spotify api to give the most accurate recommendation songs by using filtering algorithms like content based filtering. It is clear that incorporating song features to some degree will improve the accuracy of our recommendations, so we will need to find the appropriate method to utilize these features as well.

## Approach 

For clustering the dataset we use K-means. Once clustered data the pipelined data is then used for recommendation songs using content based recommendation.


## Conclustion

* Successfully built a model using K-means clustering and obtained a 98.7% accuracy and clustered data accordingly.
* Recommended songs while using the API and if heard physically the recommended songs match the vibe of the similar songs we have listened to.

## References
• https://benanne.github.io/2014/08/05/spotify-cnns.html
• https://medium.com/@david.de.hernandez/modeling-data-for-a-spotify-
recommender-system-3056997a0fc5
• https://www.popsci.com/technology/spotify-audio-recommendation-
research/
• https://www.univ.ai/post/spotify-recommendations
• https://recostream.com/blog/what-is-the-secret-of-spotify-
recommendation-system-success
