# sentimental_analysis_tweets

Implementation of text classification system by applying ML algorithms with different encoding
techniques
1. ML Algorithms: Naïve Bayes,KNN,SVM and Random Forest
2. Encoding Techniques:BOW,Bag of n grams,TF-IDF,Word embeddings using GENSIM,SPACY and
custom based embedding(CBOW and Skip-Gram)
Accuracy with different Encoding techniques:
<img width="522" alt="image" src="https://github.com/Mokshitha4/sentimental_analysis_tweets/assets/93771202/2c885e3f-ab03-460b-a565-396862cb8a47">

 Bag of words encoding model gave maximum accuracy of 71percent with SVM(Linear kernel)
and 70 percent with Random forest.
 TFIDF gave accuracy of 0.69 and 0.68 with SVM(linear) and randomforest respec􀆟vely.
 Fas􀆩ext encoding model gave 70 percent accuracy with SVM (rbf kernel)
 The reason why pre trained models gave less accuracy can be because of the out of
vocabulary words present in the dataset.
