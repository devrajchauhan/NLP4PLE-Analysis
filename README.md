# NLP4PLE-Analysis
Natural Language Processing for Personalized Learning Environments

# Yu, J. H., & Chauhan, D. (2024). Trends in NLP for personalized learning: LDA and sentiment analysis insights. Education and Information Technologies, 1-42.
# DOI: https://doi.org/10.1007/s10639-024-12988-2

# NLP Analysis of Educational Research Abstracts

## Project Overview
This project focuses on applying Natural Language Processing (NLP) techniques to educational research abstracts from the Australasian Journal of Educational Technology. The goal is to analyze and extract meaningful topics, trends, and insights using various NLP methods, including preprocessing, term frequency analysis, topic modeling, and sentiment analysis.

## Key Features
### Data Preprocessing
- Removal of special characters, stopwords, and lemmatization.
- Custom stopwords tailored for educational research contexts.
- Sentiment analysis setup using NLTK and VADER.

### Term Frequency Analysis
- Calculation of Term Frequency (TF) and Term Frequency-Inverse Document Frequency (TF-IDF) to identify significant terms in the abstracts.
- Visualization of top terms using word clouds.

### Topic Modeling
- Extraction of key topics from the abstracts to uncover trends in educational research.
- Use of pyLDAvis for interactive topic visualization.

### Sentiment Analysis
- Application of sentiment analysis to gauge the tone and emotional content of the abstracts.

## Dataset
The original dataset contained over 50,000 research papers, which were carefully filtered and processed to create this focused collection specifically relevant to educational technology research.
The abstracts are preprocessed to remove noise and prepare them for analysis.

## Dependencies
Ensure you have Python 3.x installed. The following libraries are required:
- `pandas`
- `nltk`
- `spacy`
- `scikit-learn`
- `pyLDAvis`
- `wordcloud`
- `matplotlib`

You can install these dependencies using the following command:
```sh
pip install pandas nltk spacy scikit-learn pyLDAvis wordcloud matplotlib
