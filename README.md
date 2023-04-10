# Sentiment_Analysis
Machine learning final project

This work is about the pre-processing stages, label
generation for sentiment analysis, followed by developing and
training three different deep learning models which includes
BERT, CNN and LSTM for classification of data extracted
from Reddit comments regarding ChatGPT, a language model
developed by OpenAI. The analysis was conducted on a dataset of
comments collected from various subreddits where ChatGPT was
discussed. The dataset first went through pre-processing stages
where it was first checked for missing or irrelevant data, we saw
that the data was not labelled which is a necessary requirement
for sentiment analysis so we had to utilize VADER(Valence Aware
Dictionary and Sentiment Reasoner) which is a lexicon and
rule-based sentiment analysis tool that is specifically attuned to
sentiments expressed in social media to generate labels based on
the polarity scores of the comments, we generated three labels
using VADER including Positive, Neutral and Negative. After
pre-processing and labelling, we utilized BERT,CNN and LSTM
models for classification and we were able to achieve greater than
80% validation accuracy on all three models.
