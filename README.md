# GenAI News Verifier

GenAI News Verifier is a project that leverages Gemini API and News API to classify news articles as fake or real, and answer questions based on the latest and relevant news.

## Overview

This project consists of two primary models:
1. **News Classifier**: Classifies news articles into "fake" or "real".
2. **Question Answering Model**: Provides answers to questions based on the latest and relevant news.

The project utilizes the following packages:
- `google.generativeai` for Gemini API integration
- `os` for system operations
- `NewsApiClient` from News API for fetching news
- `nltk` and `spacy` for natural language processing tasks such as tokenization and stopword removal.

## Setup

To set up the project:
1. Register for Gemini API and News API keys at their respective websites.
2. Enter your API keys in the setup section of the provided notebook (`setup.ipynb`).
3. Run the notebook to initialize the APIs and start using the models.

## Future Goals

- **Custom Language Model (LLM)**: Develop a custom language model to check facts, routing to Gemini API only when necessary.
- **Full Stack Website**: Create a web application to make the models accessible to all users.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/genai-news-verifier.git`
2. Install dependencies:
   `pip install -r requirements.txt`

## Usage

Detailed usage instructions and examples can be found in the notebook file (`GenAI News Verifier.ipynb`). 

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## Contact

For questions or feedback, please contact [me](mailto:vimalmurali03@example.com).
