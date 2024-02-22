# fake-news-detection
Many news sources contain false information and are therefore “fake news.” Because there is a lot of “fake news” articles and fabricated, misleading information on the web, we would like to determine which texts are legitimate (real) and which are illegitimate (fake). To solve this as a binary classification problem, we investigate the effectiveness of different Natural Language Processing models which are used to convert character based texts into numeric representations such as TFIDF, CountVectorizer and Word2Vec models and find out which model is able to preserve most of the contextual information about the text used in a fake news data set and how helpful and effective it is in detecting whether the text is a fake news or not.
# Dependencies
Languages: python3

Libraries: tensorflow, keras, sklearn, numpy, pandas, matplotlib, spacy, textblob, gensim, re, langid,collections, plotly

# Usage
# Directories
'*' fake-news: contains our dataset

'*' preprocessing: contains scripts that we use to preprocess our data (stop word removal, punctuation removal, etc.) and to plot the graphs that will be useful for our analysis (sentiment analysis, Pos Tags Distribution, Unigrams and Bigrams) at the preprocessing stage.

'*' train: all the pre-training and fine-tuning models are here.
