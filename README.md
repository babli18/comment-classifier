Currently in Progress: <br>
_Goal_ - To classify comments into categories irrespective of sentiment.<br>
_Data_ - The Dataset contains Googleplay comments of users using Netflix App.<br>
_Timeline of Data_ - 2018 - 2025<br>
_Source _- Kaggle<br>

_**data_preparation.ipynb** _- Contains code to clean data including feeatures, missing rows, language classification. <br>
I tried translating the language to english using opensource models but it was not upto the accuracy needed and hence change it to classifying as English and Not English.

_**clustering.ipynb** _- Contains code for general text preprocessing like lowercase, removal of stop words, emojis etc. <br>
I have used S-Bert for embedding (in order to capture and preserve the context of the sentence). Used UMAP to reduce the dimension of the embeddings to get better clusters <br>
and used HDBSCAN for clustering because it could handle various densities. I played around with clustering with and without reducing the dimensions. <br>
This is currently on hold and I will revisit again and the flow of my logic has changed.<br>

_**classify_training.ipynb**_ - Currently in progress. Intend to train a multiclass classifier.<br>

