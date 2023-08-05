# Retrieval-Chatbot
The retrieval chatbot is created using the NLTK

Description
This repository contains a retrieval chatbot implemented using the NLTK (Natural Language Tool Kit). The chatbot utilizes a data file as its knowledge base. When the user asks a question or provides input, the chatbot searches for related words in the data file and responds with an appropriate sentence. If the user's input does not match any of the words in the data file, the chatbot will return an error-predefined sentence. 

Here tokenization method is used to word_tokenize and sentence_tokenize.

Required libraries:
- NumPy, nltk, string, random
- TfidfVectorizer from sklearn.feature_extraction.text
- cosine_similarity from sklearn. metrics.pairwise



