#  extracting and preprocessing text data from Wikipedia articles related to a specified topic (geographic)

## Table of Contents

-   [Overview](#overview)
-   [Pipeline](#pipeline)
-   [Dependencies](#dependencies)
-   [Result](#result)
## Overview

Outline of the Project This venture involves extracting and prepping text material from Wikipedia entries linked to a specific subject. The main aim is to gather entries from Wikipedia, process the textual content to refine the info for subsequent analysis or applications of machine learning.

### Pipeline

-   **Data Collection**: Utilize the Wikipedia API to obtain entries based on a designated subject. The requests library is employed to make HTTP requests to Wikipedia’s API, where the feedback is sieved to extract related entries' headings and Web addresses.
-   **Text Processing**: 
    1. **Tokenization**: Divide the text into distinct words using NLTK's function for word_tokenize.
    2. **Cleaning**: Remove punctuation and alter words to lowercase to standardize the text.
    3. **Elimination of Stop Words**:Omit common stop words (for example, "and", "the") using NLTK’s given inventory to highlight more meaningful words.
    4. **Trimming and Lemmatization**: Utilize trimming and lemmatization employing NLTK’s PorterStemmer and WordNetLemmatizer to minimize words to their root forms

## Dependencies

-   Python 
-   requests
-   nltk
-   nltk.tokenize
-   nltk.corpus
-   nltk.stem


## Result

The prepped textual material is then arranged into a tidy layout appropriate for further analysis or as input into models for machine learning.


