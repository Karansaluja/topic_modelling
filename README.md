# Topic Modellling
**About the DataSet**
Here we will explore health tweets dataset to find natural clusters of
topic and subtopics using clustering algorithms. 

**About the Approach**
Below are the techiniques that'll be explored to identify the best performing technique.\
&nbsp;&nbsp;**Data Cleaning Methods** - url remover,non-alphanumeric remover,lower case, stemming,stop word removal,decontract phrases\
&nbsp;&nbsp;**Word Vectorization Methods** - Count Vectorizer, TF-IDF Vectorizer, Word2Vec\
&nbsp;&nbsp;**Modelling methods** - KMeans Clustering,Hierarchical Clustering,Latent Semantic Analysis

**Metrics Used**

Inertia, percentage reduction in inertia with increasing clusters,coherence score

**Conclusion**
KMeans with Word2Vec has superior performance as Word2Vec provides additional context from the google new corpus.10 Topics and 10 sub-topics for every topic were explored.


**Note** - To run the jupyter notebook,you will have to import Google news word2vec in the same directory. Word2Vec can be downloaded from here https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit.
