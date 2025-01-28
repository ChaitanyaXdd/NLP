# NLP Programs

Welcome to the NLP Programs repository! This repository contains a variety of Natural Language Processing (NLP) tools designed to help you preprocess and analyze text data. These tools are essential for various NLP tasks such as text classification, sentiment analysis, and more.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
  - [Stemming](#stemming)
  - [Tokenization](#tokenization)
  - [Lemmatization](#lemmatization)
  - [POS Tagging](#pos-tagging)
  - [Named Entity Recognition (NER)](#named-entity-recognition-ner)
  - [Stop Word Removal](#stop-word-removal)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Natural Language Processing (NLP) is a field of artificial intelligence that focuses on the interaction between computers and humans through natural language. Our repository includes several fundamental NLP techniques that are crucial for text preprocessing.

## Features

### Stemming
Stemming is the process of reducing words to their root form. This helps in normalizing words by removing prefixes or suffixes. For example:
- **Running** -> **Run**
- **Happily** -> **Happi**

### Tokenization
Tokenization is the process of breaking down text into individual words or phrases, known as tokens. This is a fundamental step in text preprocessing. For example:
- **"Natural Language Processing"** -> **["Natural", "Language", "Processing"]**

### Lemmatization
Lemmatization is similar to stemming but it reduces words to their base dictionary form, known as lemma. For example:
- **Running** -> **Run**
- **Better** -> **Good**

### POS Tagging
Part-of-Speech (POS) tagging is the process of assigning parts of speech to each word in a sentence, such as nouns, verbs, adjectives, etc. For example:
- **"The cat is sleeping."** -> **["The/DT", "cat/NN", "is/VBZ", "sleeping/VBG"]**

### Named Entity Recognition (NER)
Named Entity Recognition identifies and categorizes entities in text such as names, organizations, dates, etc. For example:
- **"Microsoft was founded by Bill Gates."** -> **[("Microsoft", "ORG"), ("Bill Gates", "PERSON")]**

### Stop Word Removal
Stop words are common words that are usually removed from text to focus on the important words. Examples of stop words include "the", "is", "in", etc.

## Installation
To use these NLP tools, you'll need to install the required libraries. Here's how to get started:

```bash
pip install -r requirements.txt
