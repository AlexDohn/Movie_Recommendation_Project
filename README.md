# Movie_Recommendation_Project
## Overview
Due to the effects of Covid-19, Box O' Movies a business designed around in store shopping was forced to close their doors due the loss of customers. Throughout this process, they decided they would begin to change and switch to a different route. Instead of physical movies, they would not because a streaming service. With no limit to the movies, their biggest problem was figuring out how to build a recommnedation system that will be able to connect their member to precisely the type of movies that they might enjoy. In this case, they hired my team from Dohn Co. in order to build this system or at least push them in the right direction.
## Business Problem
The streaming business is a risky field and you need have to have a one up in order to make it. As they are already barely keeping themselves a float. they need a recommendation system in order to keep their company alive. A recommendation system is perfect for that one up since it will help their members feel like they can rely on their streaming service. If the recommendation system can be accurate enough, then the members will have an easier time feeling safe with the company itself.
## Data Used
We used data from the MovieLens dataset from the GroupLens research lab at the University of Minnesota. Inside that data was four datasets in which we only used movies and ratings. Overall there were 9724 movies, 610 users, and over 100,000 ratings in the datasets.
## Models
In order to see which model would be the best for use, we used the Surprise Library in order to see the RMSE scores and compare how each different model would relate. In the eight models we compared, BaselineOnly was the best model with an RMSE score of 0.8673 (this means that the predicted rating could be 0.8673 higher or lower than the true rating).
## Conclusion
We are still in progress of completion with the recommendation system, however, we have found the best model type we could use to in order to only get about 0.86 of the true rating. Although that is already fairly good, we think in the future we will try to find ways to get that even lower. 

Please email me or feel free to go to the notebook itself if you have any questions.
