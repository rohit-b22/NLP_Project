Description:

The code performs various operations on a dataset containing research paper titles. Here is an overview of what the code does:

1. Imports the necessary libraries (numpy, pandas, os, nltk, re, WordCloud, matplotlib.pyplot, seaborn, sklearn) to perform data processing, text analysis, and visualization.
2. Loads the dataset from a CSV file named "papers.csv".
3. Performs data preprocessing steps on the title column of the dataset, including word count analysis, identifying common and uncommon words, and text normalization (lowercasing, removing punctuation, removing special characters and digits, removing stopwords, lemmatization).
4. Generates a word cloud visualization based on the processed titles.
5. Extracts features from the preprocessed titles using the CountVectorizer from sklearn.
6. Analyzes the most frequently occurring words, bi-grams, and tri-grams in the titles and generates corresponding bar plots.
7. Applies the TF-IDF transformation to the features extracted from the titles.
8. Extracts the top keywords with their corresponding TF-IDF scores for a specific document.


Dependencies:

The code requires the following dependencies-
1. numpy library
2. pandas library
3. os module
4. nltk library (requires the stopwords, wordnet, and stem packages)
5. re module
6. WordCloud class from the wordcloud library
7. matplotlib.pyplot module from the matplotlib library
8. seaborn library
9. CountVectorizer class from the sklearn.feature_extraction.text module
10. TfidfTransformer class from the sklearn.feature_extraction.text module


Usage:

To use this code, follow these steps-
1. Ensure that all the required dependencies are installed in your Python environment.
2. Place the "papers.csv" file in the same directory as the code file.
3. Run the code.

Follow the following link to download the dataset:
https://drive.google.com/file/d/1FKebCMfWCs8k85_jfmh-KhvBAyuQg7L3/view?usp=sharing

Download the zip file and extract it in the same directory as the code file.

The code will generate various visualizations and print out results related to the dataset's titles.