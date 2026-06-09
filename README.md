Social Media Sentiment Analysis using Python, NLTK & TextBlob

Project Overview

This project applies Natural Language Processing (NLP) techniques to analyze sentiments expressed in social media posts. The goal is to classify text into Positive, Negative, and Neutral sentiments while visualizing sentiment patterns and extracting insights from user-generated content.

Objectives

* Perform text preprocessing and cleaning.
* Analyze sentiment polarity using TextBlob.
* Visualize sentiment distribution.
* Generate a confusion matrix for sentiment evaluation.
* Create a word cloud to identify frequently used terms.
* Extract actionable insights from social media data.

Dataset

The dataset contains social media posts along with metadata such as:

* Text Content
* Sentiment Labels
* Platform
* Hashtags
* Likes
* Retweets
* Country
* Timestamp Information

Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* TextBlob
* Matplotlib
* Seaborn
* WordCloud
* Scikit-learn

Methodology

1. Data Loading

The dataset was imported into Python using Pandas for exploration and analysis.

2. Text Preprocessing

The text data was cleaned by:

* Converting text to lowercase
* Removing punctuation
* Removing special characters
* Removing stop words

3. Sentiment Analysis

TextBlob was used to calculate sentiment polarity scores and classify sentiments into:

* Positive
* Neutral
* Negative

4. Visualization

Several visualizations were created:

* Sentiment Distribution Chart
* Confusion Matrix
* Word Cloud
* Top Word Frequency Analysis

* ## Project Visualizations

### Sentiment Distribution

![Sentiment Distribution](images/sentiment_distribution.png)

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

### Word Cloud

![Word Cloud](images/wordcloud.png)

Results

Sentiment Distribution

Insert screenshot here.

Confusion Matrix

Insert screenshot here.

Word Cloud

Insert screenshot here.

Key Insights

* Positive sentiments dominate the dataset.
* High-engagement posts are commonly associated with positive sentiment.
* Frequently occurring words reveal common discussion themes.
* Sentiment analysis can provide valuable business intelligence for social media monitoring.

Future Improvements

* Implement machine learning models such as Logistic Regression and Naive Bayes.
* Explore deep learning approaches using LSTM networks.
* Deploy the model as a web application.
* Perform real-time sentiment analysis on social media streams.

Author

Glory Anaga

Business Management Graduate | Aspiring Data Analyst | NLP Enthusiast
