
# Learning Vector Quantization (LVQ) Implementation

This repository contains a Python implementation of the Learning Vector Quantization (LVQ) algorithm from scratch. The code is largely adapted from the tutorial by Jason Brownlee on Machine Learning Mastery.

## Description:
Learning Vector Quantization (LVQ) is a type of artificial neural network that provides a way to perform classification. It is a supervised learning algorithm that uses competitive learning to classify input vectors to target classes. LVQ networks can be used for pattern recognition problems where the goal is to classify data points into predefined categories.

## Files:
- `LVQ(fromscratch).ipynb`: The Jupyter notebook containing the LVQ implementation and demonstration.
- `ionosphere_article.csv`: The dataset used for testing the LVQ algorithm.
- `ionosphere.csv`: An additional dataset used in the notebook.

## Usage:
1. Clone this repository:
   `git clone https://github.com/csvis7/LVQ-scratch-.git`
2. Open and run the `LVQ(fromscratch).ipynb` notebook in a Jupyter environment (e.g., Google Colab).

## Ionosphere Dataset
The Ionosphere dataset predicts the structure of the ionosphere given radar return data.
Each instance describes the properties of radar returns from the atmosphere, and the task is to predict whether or not there is structure in the ionosphere.
There are 351 instances and 34 numerical input variables, 17 pairs of 2 for each radar pulse that generally have the same scale of 0-1. The class value is a string with a value of either a "g" for good return or "b" for a bad return.
Using the Zero Rule Algorithm that predicts the class with the most observations, a baseline accuracy of 64.286% can be achieved.

## Tutorial Structure
This tutorial is broken down into 4 parts:
1. Euclidean Distance.
2. Best Matching Unit.
3. Training Codebook Vectors.
4. Ionosphere Case Study.

These steps lay the foundation for implementing and applying the LVQ algorithm to predictive modeling problems.
