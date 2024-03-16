# Web Scraping and NLP Analysis Tool

This repository houses a suite of Python tools for efficient web scraping, text extraction, and in-depth natural language processing (NLP) analysis utilizing the power of the NLTK library.

## Features

- **Web Scraping**: Utilizes `BeautifulSoup` to navigate and scrape data from web pages.
- **Text Processing**: Employs `nltk` for robust text tokenization, stemming, and pattern matching.
- **Data Extraction**: Implements custom regular expressions to extract emails and phone numbers from text.
- **NLP Analysis**: Demonstrates various string matching techniques and linguistic computations.

## Installation

Ensure you have Python 3 installed on your system. Then, install the required dependencies:

```bash
pip install nltk beautifulsoup4
```

## Usage
To execute the main web scraping and NLP script, run:
``` bash
python nlp_ass1.ipynb

```

## Language Model Training and Sentence Generation
Part two of this project delves into the realm of language models, focusing on their training and the generation of probable sentences.

## Features
- **Unigram and Bigram Models**: Constructs foundational language models based on single words and word pairs.
- **Sentence Generation**: Generates coherent sentences based on both unsmoothed and smoothed language models.
- **Perplexity Calculation**: Evaluates the performance of models using perplexity as a metric.
- **Output Files**: Saves generated sentences to .txt files for external use and analysis.
  
## Running the Models
Make sure to have your .txt files ready for training and testing the models. Execute the script with:
``` bash
python Part_2.ipynb

```
## Language Models Overview

- **UnigramModel**: A basic model without smoothing.
- **SmoothedUnigramModel**: Applies Laplace smoothing to the unigram model.
- **BigramModel**: A straightforward bigram model without smoothing.
- **SmoothedBigramModelLI**: Enhances the bigram model with linear interpolation smoothing.
## Contributing
Contributions to this project are welcome. Please ensure that you adhere to standard coding practices and submit pull requests for any proposed changes.

## Acknowledgments
This toolset is designed for educational purposes and aligns with best practices for ethical web scraping.
Thank you to all the contributors and the open-source community for providing the foundational tools used in this project.
## Disclaimer
This toolkit is intended for research and educational use only. Always adhere to the terms and conditions of websites you are scraping and ensure you have permission to use the data.

