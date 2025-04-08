Currently in Progress:
Goal - To classify comments into categories irrespective of sentiment.
Data - The Dataset contains Googleplay comments of users using Netflix App.
Timeline of Data - 2018 - 2025
Source - Kaggle

**data_preparation.ipynb** - Contains code to clean data including feeatures, missing rows, language classification. 
I tried translating the language to english using opensource models but it was not upto the accuracy needed and hence change it to classifying as English and Not English.

**clustering.ipynb** - Contains code for general text preprocessing like lowercase, removal of stop words, emojis etc. 
I have used S-Bert for embedding (in order to capture and preserve the context of the sentence). Used UMAP to reduce the dimension of the embeddings to get better clusters 
and used HDBSCAN for clustering because it could handle various densities. I played around with clustering with and without reducing the dimensions. 
This is currently on hold and I will revisit again and the flow of my logic has changed.

**classify_training.ipynb** - Currently in progress. Intend to train a multiclass classifier.

