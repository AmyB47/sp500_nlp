# Text Analysis of Risk Disclosures: 2011-2020

**Description**

This project explored risk disclosures contained in annual reports of public companies in the S&P 500. Used NLP and topic modeling techniques on ten year's worth of data to identify types of risk. Preprocessed the text with NLTK to lemmatize, add stop words, and include bi-grams. Ran topic modeling on the paragraphs using CountVectorizer, TF-IDF, NMF, and LDA. CountVectorizer with NMF topic modeling yielded easily labelable types of risks. Aggregated topics for each report by weighting the paragraph topic components by number of words. Then applied K-means clustering to the weighted average topic components and grouped the reports into 8 clusters. 


**Data Sources**

* U.S. Securities and Exchange Commission (SEC) annual financial 10-K report filings from public companies.

* [U.S. SEC EDGAR](https://www.sec.gov/edgar.shtml) filings search


**Tools**

* Python

Python packages:

* urllib.request
* Pandas 
* Numpy
* Pickle
* re
* BeautifulSoup
* SciKit-Learn
* NLTK

