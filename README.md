# Introduction

This project was aimed to cluster over 2000 blogs from http://www.datasciencecentral.com/, first I used Python to get the contents of blogs, then I used tm package of R to handle texts, finally I attempted to apply unsupervised learning methods to documents clustering problem based on my previous study, exactly:

1. Scraped blogs from http://www.datasciencecentral.com/profiles/blogs using Python urllib, BeautifulSoup packages.

2. Explored the contents of blogs and preprocessed them by removing digits, punctuations and stopwords.

3. Extracted and selected useful unigrams, bigrams and trigrams from the texts using TfIdf algorithms

4. Vectorized each text with selected n-grams and visualized the texts after PCA handling.

5. Aapplied K-Means and Hierarchical methods on the dataset, and compared the results.

In order to run this project, you need install Python 2.7 along with BeautifulSoup package, Rstudio along with tm package.
