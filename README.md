# Mercor-Clothing_Similarity_Search

The goal of this project is to create a machine learning model capable of receiving text describing a clothing item and returning a ranked list of links to similar items from different websites.

Collect and preprocess data
* Use web scraping tools to gather a dataset of clothing item descriptions.
* Preprocess the text data by cleaning it.

Measure similarity
* Develop a method for extracting useful features from the text descriptions
* Compute the similarity between the input text and the texts in your database

Return ranked results
* Design a function that accepts a text string, extracts its features, computes similarities with the items in the database, ranks them based on similarity, and returns the URLs of the top-N most similar items

Deploy the function
* Deploy your function on Google Cloud Functions or Google Cloud Run

