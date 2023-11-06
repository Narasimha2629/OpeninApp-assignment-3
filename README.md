# English to Hinglish Translation Using Transformers

This repository contains a Python script that demonstrates how to perform English to Hinglish translation using the Hugging Face Transformers library. The script leverages the Helsinki-NLP OPUS-MT English-Hindi model for translation and utilizes NLTK for part-of-speech tagging.

## Key Points

- The code demonstrates the usage of the Helsinki-NLP OPUS-MT English-Hindi model for translation purposes.
- The NLTK library is utilized for part-of-speech tagging, specifically to identify nouns in the English sentences.
- The script replaces the translated nouns with the original English nouns to maintain accuracy and consistency in the translation.
- To run the script, ensure that the required libraries, such as Transformers and NLTK, are installed.
- The script can be used as a starting point for English to Hinglish translation tasks and can be further customized as per specific requirements.

## Requirements

Ensure that you have the following libraries installed:

- Transformers
- NLTK

You can install the required libraries using pip:

```bash
pip install transformers nltk
