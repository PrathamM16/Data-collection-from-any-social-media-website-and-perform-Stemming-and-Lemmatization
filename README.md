# Text Processing: Tokenization, Stemming, and Lemmatization

This project demonstrates various text processing techniques including tokenization, stemming, and lemmatization using Python and popular NLP libraries.

## Project Overview

The project processes text data from an Instagram post, performing the following steps:
1. Web scraping to extract post content
2. Text preprocessing (tokenization, stop word removal, punctuation removal)
3. Stemming using various algorithms (Porter, Snowball, Lancaster, RegExp)
4. Lemmatization using different methods (WordNet, TextBlob, spaCy, Pattern)
5. Generating a word cloud visualization

## Requirements

- Python 3.7+
- NLTK
- BeautifulSoup
- requests
- TextBlob
- spaCy
- Pattern
- WordCloud
- matplotlib

4. Download necessary NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')

Download the spaCy English model
python -m spacy download en_core_web_sm

