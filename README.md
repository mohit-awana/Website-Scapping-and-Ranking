# Website-Scapping-and-Ranking

This repository contains a lightweight Flask service along with standalone Python scripts for scraping and analyzing keywords from web pages (single-page scraping). It ranks keywords using TF-IDF scores and generates n-grams (unigrams, bigrams, trigrams). The repo can be used for keyword extraction, ranking, SEO-related analysis, and creating word clouds from the processed text.

There are three ways to analyze text data:

Flask Web Service – Launch the basic Flask app, then upload an HTML file or paste text directly.

File Analysis – Run text_analyzer_test.py from the Tests folder to analyze a text/HTML file.

URL Analysis – Run url_analyzer.py from the Tests folder to analyze content from a URL.

⚠️ Note: Some websites may block automated scraping. In such cases, download the HTML page manually and use the file analyzer instead.
