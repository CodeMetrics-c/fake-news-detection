# fake-news-detection
Many news sources contain false information and are therefore “fake news.” Because there is a lot of “fake news” articles and fabricated, misleading information on the web, we would like to determine which texts are legitimate (real) and which are illegitimate (fake). To solve this as a binary classification problem, we investigate the effectiveness of different Natural Language Processing models which are used to convert character based texts into numeric representations such as TFIDF, CountVectorizer and Word2Vec find out which model is able to preserve most of the contextual information about the text used in a fake news data set and how helpful and effective it is in detecting whether the text is a fake news or not.
# Dataset link
https://www.kaggle.com/c/fake-news/data
# Dependencies
Languages: python3

Libraries: tensorflow, keras, sklearn, numpy, pandas, matplotlib, spacy, textblob, gensim, re, langid,collections, plotly

## Usage
### Directories
* fake-news: contains our dataset

* preprocessing: contains scripts that we use to preprocess our data (stop word removal, punctuation removal, etc.) and to plot the graphs that will be useful for our analysis (sentiment analysis, Pos Tags Distribution, Unigrams and Bigrams) at the preprocessing stage.

* train: all the pre-training and fine-tuning models are here.

### Model architecture
Our model consists of two stages. In the first stages, three pre-training algorithms are applied to the cleaned text to convert them into numerical representations. And at the second stage, the numerical representations of text are fed into five fine-tuning algorithms.

### Pre-training algorithms
* CountVectorizer
* TF-IDF
* Word2Vec

### Fine-tuning algorithms
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

You can install these dependencies using pip:
pip install pandas
pip install numpy
pip install matplotlib
pip install sklearn
pip install seaborn 
pip install re 

# Usage
1. Clone this repository to your local machine:

   git clone https://github.com/CodeMetrics-c/fake-news-detection.git

2. Navigate to the project directory:

   cd fake-news-detection

3. Execute the Jupyter Notebook or Python scripts associated with each classifier to train and test the models. For example:

   python random_forest_classifier.py

The code will produce evaluation metrics and provide a prediction for whether the given news is true or false based on the trained model.

# Results
We evaluated each classifier's performance using metrics such as accuracy, precision, recall, and F1 score. The results are documented in the project files.


