# Natural_Language_Processing

In this Repository, I explore natural language processing techniques. Specifically, I use a variety of vector and transformer embedding techniques and NLP models for text classification.

Natural language processing (NLP) is a large subfield of machine learning. NLP allows data to be extracted from text. This can be implemented to perform tasks such as creating translators, performing sentiment analysis to understand product reviews on large scale, or help guide medical diagnostics.

In this project, I will be performing sentiment analysis on data from tensorflow's downloadable data sets. Specifically, I will be using Tensorflow's yelp_polarity_review dataset. This data is loaded from tensorflow so no other data files will be added to the repository at the moment. I will be talking about sentiment analysis in this notebook, but these models could also be used to extract other kinds of important text data.

If I had more time and unlimited computing power, I would try many models and tune parameters for each. Ideally, I would keep embedding and modeling methods consistent so I could compare accuracy of my models only changing one variable at a time. This project is more about personal learning than anything else so I did not worry about that.

There are 2 .ipynb files in this repository. NLP_1 contains 2 models. The first of which explores GloVe embedding and classification of text data with a CNN. The second model uses Emedding with TfidfVectorizer and Modeling with Stoichastic Gradient Descent. 

In the future, I hope to explore transformers and learn more about tensorflow BERT. I think this could be a better way of completing similiar projects.

The accuracy of the model 1 is slightly better than model 2, but I changed so many variables between the models that it doesn't really make sense to compare them. Honestly one of the main goals of this project is to make sure I have a good understanding of the different methods, advantages, and disadvantages. I chose to use the data I did because it was already split nicely for modeling. Like I said, the main goal is not to show that I can clean messy data, but to practice and understand the types of NLP models and text embedding strategies
