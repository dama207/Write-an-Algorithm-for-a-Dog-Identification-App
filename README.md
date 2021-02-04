# An Algorithm for a Dog Identification App

# Project Overview

This project is about deployment of an algorithm that has the goal of classify images. This  algorithm can detect if an image have a human or dog, also which is the breed of dog. For reach this goal, this used a neural network CNN and the technic of transfer learning. This is part of the Data Scientist Nanodegree, Udacity. 

BLOG IN MEDIUM: https://damaris-hernandez.medium.com/is-easy-to-detect-if-an-image-has-a-dog-or-human-if-it-is-a-dog-which-is-its-breed-7c0a42625445

# Problem Statement

In last years with the digital exploitation, there are many images, if we need to classify them, this could be a difficult and wasteful task. This is the reason for build several solutions to solve it  like this project.

# Metrics

The principal metric used is compare the testing values and predicted values, if these values are equal, this is counting. This result divides by total number of the values in testing dataset.

100*count(predictions == test_targets)/(total predictions)

# Methodology

# Libraries used

- sklearn.
- keras.
- numpy.
- glob.
- pandas.
- matplotlib.
- random.
- cv2.
- tqdm.

# Dataset

The data set has 8,351 total images with 133 different breeds. 

# Steps

- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write the Algorithm
- Step 6: Test the Algorithm

# Results of the analysis

The performance of algorithm is good, however, there are images that the algorithm classified wrong like the drawing of a human. This algorithm could improve with next points:

- Provide a larger training set. 
- Used a detector face human that does not need that face is well oriented. 
- Use more images of dogs in the train task.

