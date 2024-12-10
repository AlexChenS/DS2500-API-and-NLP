#### Data source: https://newsapi.org/v2
### About the project
  This project is intended to demonstrate learnings in working with APIs and some basic natural language processing. News article
  that contains chosen key words that are return and then their similarity is measured. Then set up a model for classifying further documents. 
### Methodology 
  Uses the request library to work with the NEWS API. Uses Tfidfvectorizer from sklearn to analyze their similarity, then, uses K-Means clustering for classifying
  further documents.
### How to run
  This project is intended to be run on jupyter notebooks, and its list of dependencies are as follows:
  -pandas
  -sklearn 
  -seaborn 
  -numpy
