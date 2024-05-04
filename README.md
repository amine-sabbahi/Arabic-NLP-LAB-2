# Arabic-NLP-LAB-2
# Natural Language Processing (NLP) and Word Embedding Techniques

This repository contains code examples and explanations for various Natural Language Processing (NLP) techniques and word embedding models implemented during a lab session. The provided code covers rule-based NLP using regular expressions, as well as advanced word embedding models such as Word2Vec, GloVe, and FastText.

## Introduction

In this lab, we explored different methods for analyzing and processing textual data. Our primary objectives were to understand rule-based NLP techniques for extracting structured information from unstructured text and to explore word embedding models for representing words as dense vectors in continuous vector spaces.

## Applied Approaches

### 1. Rule-Based NLP and Regex

We began by implementing a rule-based NLP approach using regular expressions. The code demonstrates how to define patterns to extract specific entities such as product names, quantities, and prices from raw text data. We then used these patterns to generate a structured bill summarizing the purchased items and their total costs.

### 2. Word Embedding Techniques

We explored fundamental word embedding techniques:
- **One-Hot Encoding:** Convert words into binary vectors.
- **Bag of Words (BoW):** Represent text data by word frequencies.
- **TF-IDF (Term Frequency-Inverse Document Frequency):** Assign weights to words based on their importance in a document.

### 3. Advanced Word Embedding Models

We delved into advanced word embedding models:
- **Word2Vec (Skip Gram and CBOW):** Learn word embeddings by predicting word context.
- **GloVe (Global Vectors for Word Representation):** Combine global co-occurrence statistics for word representations.
- **FastText:** Extend Word2Vec by considering word substructures for morphological similarities.

## Conclusion

This lab provided valuable insights into NLP techniques and word embedding models, showcasing their applications in text processing and analysis. By mastering these techniques, we can effectively extract structured information from unstructured text data and capture semantic relationships between words. These skills are essential for various NLP applications, including sentiment analysis, document classification, and machine translation.

## How to Use

Each code example is provided as a separate Python script in the repository. Simply clone the repository and run the scripts to see the implementations in action.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The code examples in this repository are adapted from various online resources and educational materials.
- Special thanks to the contributors and maintainers of the libraries used in this project.
