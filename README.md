# Scripts
An automated python script for web scraping top websites for a list of google search queries, focused on simplifying text data collection from the web and text processing for NLP models.

## Overview
The script has the following functionality:
- Query generator that generates a list of potential google searches to be passed into the web scraper. 
- Parsing queries into Google search and retrieving the top 10 links for 
this search.
- Cleaning links by removing unnecessary sections within the URL to ensure that each URL is valid.
- Extracting text content from each of the top 10 URLs for your query and saving them in _.csv_ files.
- Processing each piece of text that is not just limited to:
    1. Cleans HTML tags
    2. Converts text to lowercase
    3. Extracts alphabet characters only (a-zA-Z)
    4. Removes stop words
    5. Removes punctuations
    6. Lemmatizes given text extract
    7. Stems given text
    8. Removes whitespaces
    9. Tokenizes the text into a list of individuals words

### Query Generator

### Parsing Queries

### Cleaning Links

### Text Processing

### Storing text in _.csv_ files