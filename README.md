## DSCI_6004_02-FINAL-PROJECT by Sushma sindhe, Sai Swaroopa and AKhil Reddy
## Project: Enhancing Customer Product Review Sentiment Analysis through Deep Learning Models Incorporating Textual Features
# Overview:
In this study, we investigated the suitability of three distinct models for sentiment analysis of consumer product reviews: LSTM, BERT, and Naive Bayes. We discovered that while LSTM models are excellent at collecting sequential data, they may have trouble handling long-term dependencies. BERT models do better at comprehending text context because they make use of pre-trained representations. For sentiment analysis applications, naive Bayes classifiers offer a basic method that is easy to use. The development of interactive interfaces for presenting sentiment analysis results, domain adaptation, integrating multi-modal data sources, optimizing BERT models, and investigating ensemble approaches are some of the future research objectives.

# Project Components:
# Dataset:
Dataset of Reviews and Ratings: This dataset contains customer product reviews along with corresponding ratings (e.g., star ratings). The dataset serves as the training and evaluation data for the sentiment analysis models.
Amazon Polarity Dataset: Specifically used for training the BERT model. This dataset comprises product reviews from Amazon, labelled with positive or negative sentiments. 

# Pre-Processing of Dataset:
Some of the Text cleaning and pre-processing like Word Tokenization,coversion are the techniques performed to make the process smooth and effective.

# Natural Language Processing Models:

LSTM Model: The LSTM model is trained using the provided dataset of reviews and ratings. The training process involves optimizing the model parameters (e.g., weights and biases) to minimize a defined loss function, typically using techniques like backpropagation through time (BPTT).
BERT Model: The BERT model is pre-trained on a large corpus of text data, such as the Amazon Polarity Dataset, using self-supervised learning. Fine-tuning is then performed on the specific sentiment analysis task using the provided dataset.
Naive Bayes Model: The Naive Bayes model is trained using the traditional supervised learning approach, where the model learns the probability distribution of features given the class labels (positive or negative sentiment).

# Process 1 (step by step):
The implementation is done on Google Colab platform.

Importing all necessary libraries and modules.

Importing the dataset by accessing the link.

Implementation of Text cleaning and pre-processing techniques like Word Tokenizaion and conversion.

Train the Model

Generate Text using Trained Model

Loading the data and Training the models.

Evaluation of models by calculating the Accuracy, precision, recall for the classification task.

Comparing the performance of all the models.


# Conclusion:
Finally, our study compared the sentiment analysis of consumer product reviews using LSTM, BERT, and Naive Bayes models. While BERT showed better contextual awareness, LSTM was better at capturing sequential information. A basic baseline was offered by Naive Bayes. In order to improve sentiment analysis, future research can concentrate on optimizing BERT, investigating ensemble techniques, and incorporating multi-modal data sources.
