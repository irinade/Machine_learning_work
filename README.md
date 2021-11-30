# Machine learning work

Here are two group project on machine learning I worked on.

The frist one is deep learning on images using transfer learning. The project was to implement an object detection or recognition system from real images using an existing public pretrained neural network model and adapt it the our dataset. We choosed a dataset of around 4242 labeled images of 5 different classes of flowers. The pictures were not high resolution and were all using different proportions with no common sizes. We implemented a convolutional neural networks object recognition system working on real images, that uses model scaling, named EfficientNet, version B0, pre-trained on Stanford Dogs dataset for dog breeds recognition. We were able to make our algorithm work both for binary data (selecting only 2 different species of flowers) and multiclass data (selecting all 5 classes of flowers) and achieved a pretty good accuracy.

Dataset available here : https://www.kaggle.com/alxmamaev/flowers-recognition

The second one was to build a recommender system to predict users music preferences. It was a collaborative filtering and my team and I were dealing with 2 large files (around 12,000,000 and 90,000,000 columns respectively). This task was rendered more difficult because the datasets did not have user ratings (used for recommender system), just the column for each music clicked on by a user as an interaction matrix. I tried two different approach, the first one was to decompose the user-item interaction matrix into a dataset counting the number of appearance into the matrix of each item in order to create a rating (unfortunately I lost the code so this method is not displayed here). The other method that succeeded was to use word embedding to replace ratings (can be found in this repository). Basically we modeled a representation of users for recommender system, by using vector that encodes the music taste of each user. The users that are closer in the vector space are expected to have similar musical taste. This method was far fetched but really helpful as I could experiments with word embedding and recommender system. (For this project we took as a tutorial a nootebook from kaggle)

Dataset available here : https://www.kaggle.com/usasha/million-music-playlists

