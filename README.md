# Google bias analysis with spaCy

[Google’s algorithms discriminate against women and people of colour](https://theconversation.com/googles-algorithms-discriminate-against-women-and-people-of-colour-112516)  
or 
[plan to exterminate the White race](https://atadria.github.io/Google-bias-with-spaCy/)?  

We will try to check why Google's image search results
for the query 'happy white woman' differ from other search engines. 
We will use results from Bing for comparison. 
Results are limited by dates from 2010-01-01 to 2019-01-01. 

[Google Explains Why Some Image Search Results Look Racist](https://www.seroundtable.com/google-image-search-results-racist-26904.html)

## Dataset
[data/dataset.csv](data/dataset.csv)

title - image title  
link - url to image  
baseline - search result position  
query - search query  
engine - search engine google/bing

## Notebooks
1) [Similarity analysis with spaCy](similarity.ipynb)
2) [Dependency parsing with spaCy](dependency_parsing.ipynb)
