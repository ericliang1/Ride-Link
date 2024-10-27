# RideLink Reccomender System

This repository contains the neural collaborative filtering (NCF) model for the RideLink app and the data we used to train it. The function of the model is to calculate the similarity between two users in the form of a score. Eventually, this is used to recommend a user with the most likely students they can carpool with.

## Repository Contents
- **Neural_Collaborative_Filtering_Model_Ride_Link.ipynb**: Jupyter notebook containing the NCF model architecture, training process, and evaluation
- **ridelink_data.csv**: Training data used to train the NCF model. Features include: distances from school, flexibility, commute and leaving times, distance between users, and similarity scores

## Features
- predicts similarity score between two users with 96% accuracy
- recommends potential carpool partners using predicted similarity scores
