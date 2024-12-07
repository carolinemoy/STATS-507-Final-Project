# STATS-507-Final-Project
This project is the culmination of STATS 507 Fall semester 2024. Here I create a Multi-Layer Perceptron for Binary Text Classification for analyzing the rhetoric of Democrat versus Republican politicians of American politics. I will do this through a data set found on Hugging Face which has 140,000 tweets, which are pre-processed with the text and party of the individual. However, word vectors had to be implemented to analyze the data and it was achieved through Word2Vec. In this project, I create a Multi-Layer Perceptron for word vectors of length 100 which are pooled through the means of each corresponding entry. I compared this to a simpler model, logistic regression. Then, I tested these methods on vectors of length 100 which had been pooled in different ways and vectors of different lenght (mean pooling). There are many future expansions to this project, but this initial starting point allowed me to understand the architecture of neural networks using Python, as well as determining if there are language differences between the tweets of Democrats and Republicans. 
