# Summarizer and translator
News Summarizer and Translator from English to Arabic, that can scrape news articles from almost any international news website.

### the idea
Facilitate access to international news to Arabic readers. Inspired by millions of Arabs who can't read English and want to be aware of international politics, events, etc...

### The project's architecture consists of:

- Scraping news website
Newspaper3k library is a simple and very powerful library for scraping almost any news website without the need to explicitly provide any HTML tags.

- Summarize latest news articles
Was done using BART-large model which is pre-trained on English language, and fine-tuned on CNN Daily Mail dataset.

- Translate articles summary
Was done using mBART-50 many to many multilingual machine translation model.

### colab 
https://colab.research.google.com/drive/1sojJvxrZSviImUrWTP3FX7o5TL54WQ5i?usp=sharing
