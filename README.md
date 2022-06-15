# Rule-based-chatbot

The chatbot process is split into two steps :

- Intent retrieval from questions and responses using Topic modeling (LDA)
pip install gensim==3.8.3

- Similarity search by vectorizing the answers and compute the closest answer to the question using Doc2Vec
We save the model d2v.model for vectorization 
