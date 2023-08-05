# Retrieval-Chatbot
The retrieval chatbot is created using the NLTK

#Description
This is implemented using the NLTK (Natural Language Tool Kit). Here the data is given as a file. so when the user asks anything the chatbot will find a related word in the data file and will return a sentence. If the user provides any input which doesn't match any of the words in the data file then the bot will return a error-predefined sentence. 

Here tokenization method is used to word_tokenize and sentence_tokenize.

Required libraries:
- NumPy, nltk, string, random
- TfidfVectorizer from sklearn.feature_extraction.text
- cosine_similarity from sklearn. metrics.pairwise



