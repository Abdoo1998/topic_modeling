# Topic Modeling with Latent Dirichlet Allocation (LDA) using scikit-learn
## This project demonstrates how to perform topic modeling using Latent Dirichlet Allocation (LDA) in Python with scikit-learn. The project uses the sklearn library for training the LDA model and pyLDAvis for visualizing the results.

Requirements
Python 3.x
pandas
sklearn
pyLDAvis
nltk
matplotlib
Data
The dataset used in this project is a collection of articles in csv format, you can use your own dataset and adjust the code to fit your data.

Installation
Install the required libraries by running pip install -r requirements.txt
Usage
Run the topic_modeling_LDA_sklearn.py script to train the LDA model on the dataset.
The script will output the top words for each topic and visualize the results using pyLDAvis.
You can adjust the number of topics, and the number of components as you prefer.
Results
The results of the LDA model will be the top words for each topic and the corresponding weights, these words can indicate the main topic of the articles. Additionally, the visualization will help you to understand the relationships between the topics and the words.

Additional Resources
Latent Dirichlet Allocation (LDA) - A Beginner's Guide
Topic Modeling with scikit-learn
