# NLP-Chatbot
## A basic chatbot trained from word embeddings and sequence-to-sequence model.<br>

The chatbot uses datasets from Microsoft BotBuilder Personality Chat Datasets, consisting of three personalities, "comic", "friend", and "professional". The chatbot is designed to run on Google Colab.<br><br>
First we preprocess the data, removing punctuations and decapitalizing the data, chopping down sentences into tokens for further model training.
<br><br>
Then we perform word embeddings with gensim wor2vec, and is hence used for seq2seq model training. After we trained three different models, the chatbot is ready to function. Once the chat is finished, a .txt file of the chat is automatically downloaded.
<br><br>
The .ipynb file can also be accessed from this link:<br>
https://drive.google.com/open?id=1ijeJVQKkHdLW5jJnPgkn9nvu1DQvJEn6

