# 🧠 NLP Basics with spaCy, NLTK & WordCloud

This project demonstrates Natural Language Processing (NLP) fundamentals using popular Python libraries like spaCy, NLTK, Matplotlib, and WordCloud.
It covers tokenization, stopwords removal, lemmatization, stemming, frequency analysis, POS tagging, and visualizations.

## 🚀 Features Implemented
✔️ Text Preprocessing

- Tokenization
- Stopword removal
- Lemmatization (spaCy)
- Stemming (NLTK – Porter Stemmer)

  ✔️ Exploratory NLP Tasks

- Compare lemmatization vs stemming
- Word frequency extraction
- Generate a Word Cloud
- Part-of-Speech (POS) frequency visualization
- Named Entity Recognition (NER)
- Dependency parsing with spaCy’s displacy

# 📝 Workflow Overview

1. Load English NLP Model
-> nlp = spacy.load("en_core_web_sm")

2. Prepare text and process it
-> doc = nlp(text)

3. Token Analysis
-> Text, lemma, part of speech, dependency, stopword flag

4. Lemmatization vs Stemming
-> Shows differences using spaCy and NLTK

5. Clean Tokens for Visualization
-> clean_tokens = [token.lemma_.lower() for token in doc if token.is_alpha and not token.is_stop]

6. Word Frequency Bar Plot

7. Word Cloud Generation

8. POS Tag Distribution

9. NER & Dependency Parsing
-> Visualized using displacy

# 📊 Visual Outputs

* Bar chart of most frequent words
* Word cloud showing prominent terms
* POS tag distribution
* NER and dependency parse charts


