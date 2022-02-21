# Embeddings
These notebooks are devoted to embeddings. 

## Seminar
In seminar notebook quora questions are analysed. 
It is shown how to:
 - tokenize the data
 - load word2vec models
 - look up vectors for words and find similar words to other words
 - vizualize word vectors after dimensionality reduction using PSA and t-SNE
 - vizualize phrases by taking average of vectors for all tokens in the phrase 
 - build simple "similar question" engine with phrase embeddings

## Homework
In homework notebook demonstrated how to make machine translation system without using parallel corpora, alignment, attention and other cool tech.
To show that:
 - russian and ukranian word2vec embeddings are loaded
 - russian and ukranian word pairs are loaded and split to train and test sets
 - embedding space mapping performed in a two ways:
   - using multiple linear regression and 
   - by finding optimal orthogonal transformatino using SVD
 - precision function is created to estimate the quality of transformation
 - simple word-based translator is made

**Additionally**:
  - russian and ukranian fastText embeddings are loaded
  - the size of vocabulary for fastText embeddings is approx 3 times bigger than for gensim embeddings, so the quality of translation became better
