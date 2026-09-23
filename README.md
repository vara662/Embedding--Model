
# Semantic Similarity Using Sentence Transformers

## Overview

This project demonstrates semantic similarity analysis using Natural Language Processing (NLP). It uses the Sentence Transformers library to convert sentences into numerical embeddings and calculates the semantic similarity between sentences using cosine similarity.

The project uses the `all-MiniLM-L6-v2` pre-trained model to generate sentence embeddings and Scikit-learn to calculate cosine similarity scores.

## Objectives

- Convert text sentences into numerical embeddings.
- Understand sentence representation using transformer models.
- Calculate semantic similarity between sentences.
- Identify sentence pairs with similar meanings.
- Demonstrate a practical NLP application using Python.

## Technologies Used

- Python
- Sentence Transformers
- Scikit-learn
- Natural Language Processing
- Transformer Models

## Model Used

### all-MiniLM-L6-v2

The `all-MiniLM-L6-v2` model is a pre-trained Sentence Transformer model used to generate meaningful vector representations of sentences.

Each sentence is converted into a **384-dimensional embedding**.

## How the Project Works

The project follows these steps:

1. Load the Sentence Transformer model.
2. Define a collection of sentences.
3. Convert the sentences into embeddings.
4. Calculate cosine similarity between all sentence embeddings.
5. Compare the similarity scores.
6. Display sentence pairs with a similarity score greater than `0.5`.

## Example Sentences

The project uses sentences such as:

```text
I love playing cricket.
I enjoy playing football.
I like watching cricket matches.
I want to become a software developer.
Technology is changing our daily lives.
Machine learning is a branch of artificial intelligence.
Python is a popular programming language.
The restaurant serves delicious food.
````

## Cosine Similarity

Cosine similarity measures the similarity between two vectors.

A higher similarity score indicates that two sentences have a more similar semantic meaning.

The project uses:

```python
cosine_similarity(embeddings)
```

to calculate the similarity between all sentence embeddings.

## Project Structure

```text
Semantic-Similarity/
│
├── semantic_similarity.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd Semantic-Similarity
```

Install the required libraries:

```bash
pip install sentence-transformers scikit-learn
```

## Running the Project

Run the Python file using:

```bash
python semantic_similarity.py
```

## Output

The program displays:

* Total number of sentences
* Embedding dimension
* Numerical embeddings for each sentence
* Semantically similar sentence pairs
* Cosine similarity scores

Example:

```text
Total number of sentences: 8
Embedding dimension: 384

--- Semantic Similarity ---

Sentence 1: I love playing cricket.
Sentence 2: I like watching cricket matches.
Similarity: 0.xxxx
```

The exact similarity scores depend on the generated embeddings and model version.

## Applications

Semantic similarity techniques can be used in:

* Search engines
* Recommendation systems
* Question-answering systems
* Document comparison
* Chatbots
* Duplicate text detection
* Information retrieval
* Natural Language Processing applications

## Learning Outcomes

Through this project, I learned how to:

* Work with pre-trained transformer models.
* Generate sentence embeddings.
* Represent natural language as numerical vectors.
* Calculate cosine similarity.
* Apply NLP techniques to compare the meaning of sentences.

## Future Enhancements

Possible improvements include:

* Adding a user interface for entering custom sentences.
* Displaying similarity scores in a visual format.
* Comparing multiple transformer models.
* Building a semantic search system.
* Adding sentence clustering functionality.

## Author

Varalakshmi Karthick Kumar
