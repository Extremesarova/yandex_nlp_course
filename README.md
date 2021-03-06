# [NLP Course | For You by Lena Voita](https://lena-voita.github.io/nlp_course.html) + [YSDA Natural Language Processing course](https://github.com/yandexdataschool/nlp_course)

## Contents

* [Week 1](https://github.com/Extremesarova/yandex_nlp_course/tree/main/week01_embeddings) - Embeddings
  * [Fun with Word Embeddings](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week01_embeddings/seminar.ipynb)
    * Tokenization
    * Word2Vec embeddings
    * GloVe embeddings
    * Visualizing word vectors using PCA and t-SNE
    * Finding similar questions
  * [Multilingual Embedding-based Machine Translation](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week01_embeddings/homework.ipynb)
    * Word2Vec embeddings
    * Embedding space mapping + orthogonal Procrustean problem
    * Improving multilingual embedding-based MT with FastText embeddings
* [Week 2](https://github.com/Extremesarova/yandex_nlp_course/tree/main/week02_text_classification) - Classification
  * [Large scale text analysis with deep learning](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week02_text_classification/seminar.ipynb)
  * [Prohibited Comment Classification](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week02_text_classification/homework_part1.ipynb)  
  Tackle this problem using both classical NLP methods and embedding-based approach:
    * BOW from scratch implementation
    * TF-IDF from scratch implementation
    * Naive Bayes from scratch
    * TF-IDF + Logistic Regression + Hyperparameter Grid Search
    * FastText embeddings + Logistic Regression + Hyperparameter Grid Search
  * [Salary prediction](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week02_text_classification/homework_part2.ipynb)  
  The task is to predict salary based on the different text and categorical features:
    * Exploratory Data Analysis
      * Categorical Columns Encoding
      * Target transformation
  * Modeling:
    * Baseline: Custom PyTorch dataset + Custom Transforms + Fusion model (Title Encoder + Description Encoder + Categorical Encoder )
    * Improved model: *In progress*
  * Explaining model predictions: *In progress*
* [Week 3](https://github.com/Extremesarova/yandex_nlp_course/tree/main/week03_language_modeling) - Language Modeling
  * [Building n-gram language model using titles and summaries from ArXiv articles](https://nbviewer.org/github/Extremesarova/yandex_nlp_course/blob/main/week03_language_modeling/seminar.ipynb)  
    * Sampling with temperature.
    * Language Model evaluation: Perplexity.
    * Language Model smoothing: Laplace.
  * [Neural left-to-right LMs](https://github.com/Extremesarova/yandex_nlp_course/blob/main/week03_language_modeling/homework_pytorch.ipynb):
    * Preparing dataset for training (building char-level vocabulary)
    * FixedWindowLanguageModel using CNN (training, evaluation, generation)
    * Cross Entropy Categorical Loss implementation
    * RNN LanguageModel using LSTM (training, evaluation, generation)
    * Implemented Nucleous sampling
* Week 4 - Seq2Seq

## To-do

* week 2 (Text Classification):
  * Practice:
    * Homework part 2 - *in progress*
  * Theory:
    * Analysis and Interpretability
    * Research Thinking
    * Related Papers
* week 3 (Language Modeling):
  * Practice:
    * Seminar - Fix *Kneser-Ney smoothing*  
  Look [here](https://lena-voita.github.io/nlp_course/language_modeling.html#related_papers) at the bottom of the page for reference formula
    * Homework - Implement Beam Search + Ultimate LM
* week 4 (Seq2Seq)
