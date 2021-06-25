# Cancer_Class_Predicition
Given two categorical features and one text feature, task is to classify the one of nine cancer category
Data can be found at https://www.kaggle.com/c/msk-redefining-cancer-treatment/

As the text feature was quite large, I took 1000 rows for training. 
After trying almost everything, be it Naive Bayes, Logistic Regression and Random forest with hyperparameter optimisation, upsampling, ngrams, BOW, TFIDF, Word2Vec I could achieve a maximum recall of ~65% with minimum log loss of ~1.1

What sursprised me was that I got better results on TFIDF than Word2Vec
