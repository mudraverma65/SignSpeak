# SignSpeak: Vision System for Sign Language Chatbot

## Introduction
This project focuses on developing a vision system to enable a chatbot to communicate using sign language. The primary task involves recognizing signs using the Sign Language MNIST dataset, which contains images of hand signs and their respective alphabet letters. This was developed as Assignment 3 for course CSCI6515: ML for Big Data.

## Dataset Preparation
1. **Data Transformation:**
   - Source: https://www.kaggle.com/datasets/datamunge/sign-language-mnist?resource=download
   - Applied data transformation methods to prepare the Sign Language MNIST dataset.
   - Explained the rationale behind the chosen transformation method.

## K-Means Clustering
1. **Algorithm Application:**
   - Applied the k-means algorithm to the dataset.
   
2. **Cluster Optimization:**
   - Changed the number of clusters from 10 to 200 with a step size of 10.
   - Showed the performance based on accuracy and the objective function value for each cluster number.
   
3. **Optimal Number of Clusters:**
   - Determined the optimal number of clusters and justified the answer.

## Fuzzy K-Means Clustering
1. **Algorithm Application:**
   - Applied the fuzzy k-means algorithm to the dataset.
   
2. **Performance Analysis:**
   - Changed the number of clusters from 10 to 200 with a step size of 10.
   - Showed the performance based on accuracy and the objective function value.
   
3. **Fuzzifier Variation:**
   - Changed the fuzzifier value from 1 to 5 with a step size of 1.
   - Compared k-means and FCM based on the achieved results.

## Feedforward Neural Network
1. **Model Design:**
   - Developed a Convolutional Neural Network (CNN) with a maximum of 10 hidden layers.
   - Specified kernel sizes, number of filters, activation functions, learning rate, optimization, and loss functions.
   
2. **Model Evaluation:**
   - Trained and tested the network using the Sign-MNIST dataset.
   - Plotted the confusion matrix and evaluated the classification model's performance.

## Conclusion
This project aims to enhance communication by creating a chatbot capable of understanding sign language. Through k-means and fuzzy k-means clustering, as well as the implementation of a Convolutional Neural Network, we explored different approaches for recognizing hand signs. The README provides an overview of the dataset preparation, clustering experiments, and the development of the neural network.
