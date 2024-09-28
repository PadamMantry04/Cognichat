# Cognichat

Conversational modeling plays a crucial role in Natural Language Processing (NLP) and Artificial Intelligence (AI). A conversational agent, or chatbot, is a software application designed to communicate with users through natural language, leveraging machine learning and NLP techniques. Building an intelligent chatbot remains a significant challenge in AI, as early models relied on predefined rules, such as regular expressions. However, this rule-based approach is now impractical, as it requires an overwhelming number of rules to simulate human-like conversation.

This project features a neural network-driven chatbot powered by Long Short-Term Memory (LSTM) models for encoding and decoding. Designed as an open-domain system, the chatbot can handle a wide range of general conversational queries. Central to the chatbot’s design are word embeddings, with Glove and Skip-Gram models used to capture semantic relationships between words. Trained on the extensive Cornell Movies dataset, the model is fully automated and learns without manually crafted rules, allowing it to adapt and respond to diverse conversational inputs independently of specific domains.


# Dataset
The dataset consists of two key files: movie_conversations and movie_lines. Due to the large size of the movie_conversations file, it couldn’t be uploaded to GitHub directly, so it has been compressed into a zip file, movie_conversations.zip.

# Code Files
Chatbot using Glove Embeddings and LSTM
This file contains the LSTM-based model trained with Glove word embeddings. The embeddings are loaded using the glove.6B.50d file. Given that the model requires 100 training epochs, which is time-consuming, the trained model has been saved as lstm_model_glove_embeddings.h5 for easy reuse. This file can be loaded to interact with the chatbot without retraining the model.

Chatbot using Skip-Gram Embeddings and LSTM
This file features the LSTM model trained with Skip-Gram embeddings. Similarly, the model was trained for 100 epochs, and the final version is saved as lstm_model_skip_embeddings.h5 to enable interaction with the chatbot without the need for re-training.

Glove Embeddings File
The glove.6B.50d file, due to its large size, couldn't be uploaded even after compression. It can be accessed via the following link: Glove 6B 50d on Kaggle.
