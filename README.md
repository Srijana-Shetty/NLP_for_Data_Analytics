# 🧠 NLP Basics with spaCy, NLTK & WordCloud

This project demonstrates Natural Language Processing (NLP) fundamentals using popular Python libraries like spaCy, NLTK, Matplotlib, and WordCloud.
It covers tokenization, stopwords removal, lemmatization, stemming, frequency analysis, POS tagging, and visualizations.

## 🚀 Features Implemented
### ✔️ Text Preprocessing

- Tokenization
- Stopword removal
- Lemmatization (spaCy)
- Stemming (NLTK – Porter Stemmer)

### ✔️ Exploratory NLP Tasks

- Compare lemmatization vs stemming
- Word frequency extraction
- Generate a Word Cloud
- Part-of-Speech (POS) frequency visualization
- Named Entity Recognition (NER)
- Dependency parsing with spaCy’s displacy

## 📝 Workflow Overview

#### 1. Load English NLP Model
- nlp = spacy.load("en_core_web_sm")

#### 2. Prepare text and process it
- doc = nlp(text)

#### 3. Token Analysis
- Text, lemma, part of speech, dependency, stopword flag

#### 4. Lemmatization vs Stemming
- Shows differences using spaCy and NLTK

#### 5. Clean Tokens for Visualization
- clean_tokens = [token.lemma_.lower() for token in doc if token.is_alpha and not token.is_stop]

#### 6. Word Frequency Bar Plot

#### 7. Word Cloud Generation

#### 8. POS Tag Distribution

#### 9. NER & Dependency Parsing
- Visualized using displacy

## 📊 Visual Outputs

* Bar chart of most frequent words
* Word cloud showing prominent terms
* POS tag distribution
* NER and dependency parse charts

<img width="300" height="300" alt="Screenshot 2025-11-20 114834" src="https://github.com/user-attachments/assets/34787069-49f1-4e6c-8033-4417abb4caf3" />
<img width="300" height="300" alt="Screenshot 2025-11-20 114834" src="https://github.com/user-attachments/assets/a61a1cf5-c11c-4409-ae99-6de7fa74c17c" />
<img width="400" height="400" alt="Screenshot 2025-11-20 114355" src="https://github.com/user-attachments/assets/62803c52-3e60-44e1-a869-3348f73f688f" />



