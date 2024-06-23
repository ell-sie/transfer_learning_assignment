# End-to-End Multi-Class Dog Breed Classificaion

This notebook builds an end-to-end multiclass image classifier using TensorFlow 2.0 and Tensorflow Hub.

# 1. Problem

> Identify the bread of a dog given in an image of a dog.

# 2. Data

The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

# 3. Evaluation

For each image in the test set, you must predict a probability for each of the different breeds.

https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

# 4. Features

Some information about the data:


*   We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
*   There are 120 breeds of dogs (this means there are 120 different classes).
*   There are around 10,000+ images in the training set (these images have labels)
*   There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).
