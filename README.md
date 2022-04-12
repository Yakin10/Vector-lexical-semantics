# Vector-semantics
 Natural Language Processing and Understanding Assignment 3

# Requirement
1) NLTK
2) gensim
3) matplotlib
4) sklearn
5) pandas
6) pytrec_eval

# overview
This code forms a dictionary of similar from SimLex-999 and use it as base of evaluation. Two corpus (Romance and Adventure) from nltk is used to train TF-IDF model and Word2Vec model. TF-IDF model uses Cosine Similarity to calculate top 10 similar words and Word2Vec model uses its own most_similar() funtion to retrive 10 most similar words.

# result
NDCG for TF-IDF Model
![NDCG for TF-IDF model](https://github.com/Yakin10/Vector-semantics/blob/main/Images/ndcg_tf-idf.png)

NDCG for Word2vec Model on Romance Corpus
![NDCG for Word2Vec Model on Romance Corpus](https://github.com/Yakin10/Vector-semantics/blob/main/Images/ndcg_romance.png)

NDCG for Word2vec Model on Adventure Corpus
![NDCG for Word2Vec Model on Adventure Corpus](https://github.com/Yakin10/Vector-semantics/blob/main/Images/ndcg_adventure.png)
