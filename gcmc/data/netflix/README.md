# Team 18 Mary Abikoye, Mengmeng Li, Jingwen zhou

# Graph Convolutional Matrix Completion for Netflix Movie Recommendation System

This is the Tensorflow based implemention of Graph Convolutional Matrix Completion for Recommender systems.

## Dataset

Please download the dataset to the floder 'gcmc/data/netflix' frist [Netflix Prize Dataset](https://www.kaggle.com/code/laowingkin/netflix-movie-recommendation/data)

## Requirements

- TensorFlow (1.4)
- pandas

## Run the Code

- We used Google Colab to run the code and train the model
- Train_Netflix.ipynb is the code for training the model based on the Netflix Dataset
- Train_MovieLens1M.ipynb is the code for training the model based on the MovieLens 1M Dataset

## About the Code

We wrote the code for pre-processing the Netflix dataset, data filtering and screening. The code of building the model is wrote by
Rianne van den Berg, Thomas N. Kipf, Max Welling, [Graph Convolutional Matrix Completion](https://arxiv.org/abs/1706.02263) (2017).
We tuned different hyper-parameters such as dropout rate and retrained the model.

```

```
