# topic_modeling_wikipedia

This project demonstrates the preprocessing and clustering of 694 Wikipedia articles related to the topic "Linear algebra".

The source data were scraped from relevant Wikipedia articles, including all the pages hyperlinked within the page titled "Linear algebra" and all the articles listed under the category page "Linear algebra" and "Numerical analysis". (The categories were found at the bottom of the page "Linear algebra". ) 

The articles were clustered based on the Latent Dirichlet Allocation (LDA) model, and similar articles could be queried from the clusters. At the end, a similarity matrix was formed based on the corpus matrix resulting from applying a combined tfidf and Latent semantic indexing (LSI) model to the document_term matrix. 
