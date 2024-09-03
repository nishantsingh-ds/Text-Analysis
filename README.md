
# Web Text Analysis Project

## Overview

This project involves extracting, processing, and analyzing text data from a set of web pages to gain insights into their sentiment, readability, and complexity. Using web scraping, text processing, and sentiment analysis techniques, the project generates various textual metrics and statistics.

## Project Components

1. **Web Scraping**:
   - Extracts text data from specified web pages.
   - Utilizes `requests` to fetch HTML content and `BeautifulSoup` to parse and extract relevant text (titles and paragraphs).

2. **Text Processing**:
   - Cleans and prepares the text for analysis.
   - Employs `nltk` for tokenization, lemmatization, and stop word removal.
   - Saves the cleaned text data into individual files.

3. **Text Analysis**:
   - Performs sentiment analysis using `nltk`’s `SentimentIntensityAnalyzer` to compute positive, negative, and neutral sentiment scores.
   - Calculates various metrics including:
     - Polarity Score
     - Subjectivity Score
     - Average Sentence Length
     - Percentage of Complex Words
     - Fog Index
     - Average Word Length
     - Total Syllables and Complex Word Count
     - Count of Personal Pronouns

4. **Data Organization**:
   - Compiles the computed metrics into a structured `pandas` DataFrame.
   - Outputs the DataFrame for review and analysis.

## Installation

To run this project, you will need to have Python installed along with the following libraries:

- `requests`
- `beautifulsoup4`
- `pandas`
- `nltk`

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas nltk
```

## Usage

1. **Configure URLs**:
   - Define the list of URLs from which you want to extract and analyze text data.

2. **Run the Script**:
   - Execute the Python script to perform web scraping, text processing, and analysis.

3. **Review Results**:
   - Check the output DataFrame printed to the console for textual metrics and statistics.


urls = ['https://example.com/page1', 'https://example.com/page2']


## Contributing

Feel free to contribute to this project by submitting issues or pull requests. 

## Acknowledgements

- This project uses `nltk` for natural language processing and sentiment analysis.
- Thanks to the contributors and maintainers of `beautifulsoup4` and `requests`.
