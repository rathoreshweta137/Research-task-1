# Research-task-1

Self-Harm Detection using Sentiment Analysis, Topic Modeling, and Clustering

This project aims to analyze a dataset of self-harm-related posts and identify patterns in the text using various techniques, including sentiment analysis, topic modeling, and clustering. The goal is to gain insights into the language and emotions behind self-harm, which can be useful for designing interventions or support systems.

Prerequisites : 
Python 3.x,
Pandas,
NumPy,
NLTK,
TextBlob,
Scikit-learn,
Matplotlib.

In the given task, I have used various unsupervised learning techniques to analyze the self-harm dataset, which are:

Data :
The dataset used in this project is a CSV file called selfharm.csv, which contains two columns: title and text. These columns contain the title and text of various posts related to self-harm, taken from an online forum.

Feature Selection:
To narrow down the dataset and focus on the most relevant information, we selected only the title and text columns from the original dataframe using the following code:

Data Cleaning: As the dataset contains unstructured text data, data cleaning is the first step to convert the text data into a structured format. The cleaning process involves removing special characters, digits, stop words, and performing stemming and lemmatization to normalize the data.

Sentiment Analysis:
We will perform sentiment analysis on the text using the TextBlob library. We will create a new column in the dataframe called 'sentiment' that contains the sentiment score of each post.

Topic Modeling:
Topic modeling is used to identify the hidden topics in the text data. In this task, I have used Latent Dirichlet Allocation (LDA) algorithm to identify the latent topics in the self-harm dataset. We will use the CountVectorizer to convert the text data into a matrix of token counts.

Clustering: Clustering is the process of grouping similar data points together. In this task, I have used K-Means clustering algorithm to cluster the self-harm dataset based on the text data.

Visualization:
I'm using Scatter plots which is used to represent data: These can be used to show the relationship between sentiment and cluster, as shown in the code.
We will visualize the results , you can see outputs in jupyter notebook code .

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Based on the analysis of the self-harm dataset using unsupervised learning techniques, we can draw the following conclusions and interpretations:

Sentiment Analysis: The sentiment analysis of the self-harm dataset using the VADER tool shows that the majority of the posts have a negative sentiment. This indicates that self-harm is associated with negative emotions such as depression, anxiety, and stress.

Topic Modeling: The topic modeling of the self-harm dataset using the LDA algorithm identified several latent topics such as depression, self-harm scars, suicide, anxiety, and self-harm methods. This indicates that people who engage in self-harm may have different reasons and motivations for doing so.

Clustering: The clustering of the self-harm dataset using K-Means algorithm shows that the dataset can be divided into several clusters based on the text data. This indicates that the self-harm dataset is diverse and contains a variety of posts related to self-harm.


//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Here are some additional analyses that can be performed on the self-harm dataset using unsupervised learning techniques:

Word Embeddings: Word embeddings can be used to represent the text data in a numerical format, which can then be used for further analysis such as clustering and classification. This technique can help identify similar words and topics in the dataset and can also be used to measure the semantic similarity between words.

Network Analysis: Network analysis can be used to identify relationships and connections between different words and topics in the dataset. This technique can be useful in identifying the most important and influential words and topics in the dataset and can also help identify communities of related posts.










