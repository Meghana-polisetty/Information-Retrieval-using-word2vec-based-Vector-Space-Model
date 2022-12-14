# Information-Retrieval-using-word2vec-based-Vector-Space-Model
Performed information retrieval using Word2Vec based vector space model with 367k queries and 3.2M documents and performed pre-processing steps like converting text into lower case, expanding contractions, removing stop words, lemmatizing texts.

Information Retrival

Information Retrieval is the process of finding desired documents from a collection of documents.

![image](https://user-images.githubusercontent.com/90289879/198734884-382146c1-486c-4a43-b03d-e71c17ce1ef2.png)

The way this works is that the user inputs his need in the form of text(query) in the information retrieval system. The system then processes this query and finds the relevant documents from the existing collection of documents(corpus). These relevant documents are then sent to the user in the decreasing order of relevance. In this whole process, the rank of documents returned determines how good or bad our results are.

For example, you go to an e-commerce website and search for an iPhone, and the website shows you the iPhone charger and back cover first and then shows you the smartphone. Now, tell me one thing, are charger and back cover related to the query?-Yes they’re somewhat. But, Are they most relevant to the query? No, the smartphone is most relevant to the input query, so it should be shown to the user first.

You see, in information retrieval problems, just returning relevant documents is not the task. Instead, you have to return the most relevant ones first, followed by less relevant documents. This is known as document ranking. There are multiple ways of ranking documents for a query, but in this article, we’ll only use the vector space model, which is an unsupervised method.

![image](https://user-images.githubusercontent.com/90289879/198734925-36f80e45-54a6-43fc-8ac0-d9dba9fd9181.png)

