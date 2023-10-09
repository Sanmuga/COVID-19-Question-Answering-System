
# COVID-19 Question Answering System

## Overview

The COVID-19 Question Answering System is a Python program designed to provide answers to user queries related to the COVID-19 pandemic. It utilizes natural language processing (NLP) techniques and information retrieval methods to extract relevant information from a provided text source and respond to a range of questions.

## Features

- **Question Types:** The system can handle various question types, including "WHO," "WHERE," "HOW MANY," and more, to extract specific information.

- **Text Preprocessing:** The program preprocesses the input text data, including stemming and removing stopwords for better analysis.

- **TF-IDF Vectorization:** It computes the TF-IDF matrix to represent the importance of terms in the text and uses it to find relevant sentences.

- **Cosine Similarity:** The program calculates cosine similarity between user questions and sentences in the text to identify the most relevant answers.

- **Answer Extraction:** It extracts answers based on the context and type of question, delivering accurate responses.

## Usage

1. Clone the repository to your local machine.

2. Ensure you have the required Python libraries installed (see `requirements.txt`).

3. Provide your text source (e.g., COVID-19 Wikipedia data) by replacing `wikipedia.txt` with your source file.

4. Run the program by executing the Python script: `python covid19_qa.py`.

5. Input your questions when prompted, and the system will provide answers based on the provided text source.

## Example Questions

- "How many cases have been reported and how many deaths have occurred in various countries?"
- "What are the common symptoms and how long should I wash my hands?"
- "When was the first case discovered and where was the virus first identified?"

## License

This program is licensed under the [MIT License](LICENSE).

## Acknowledgments

The COVID-19 Question Answering System was developed as part of a project to provide accessible and accurate information about the COVID-19 pandemic. Special thanks to the open-source NLP and information retrieval libraries that made this project possible.

---

You can adapt and expand this README file to include more details, installation instructions, and usage guidelines based on your project's needs.
