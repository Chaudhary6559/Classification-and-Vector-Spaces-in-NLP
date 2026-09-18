# Naive Machine Translation and Locality Sensitive Hashing (LSH)

This project explores **cross-lingual word embedding alignment** for a simple machine translation system and uses **Locality Sensitive Hashing (LSH)** to perform approximate nearest-neighbor search on document embeddings.

Completed as **Assignment 4** of the *Classification and Vector Spaces in NLP* course, the notebook demonstrates how vector-space methods can support translation, semantic search, and efficient similarity-based retrieval.

---

## 📌 Project Overview

This assignment introduces two applications of word embeddings:

1. **Naive Machine Translation:** Align English and French word embeddings using a learned linear transformation, then identify likely translations through nearest-neighbor search.
2. **LSH and Document Search:** Represent tweets as document vectors and use locality-sensitive hashing to find similar tweets more efficiently than exhaustive similarity search.

The project connects word embeddings and vector similarity with practical NLP tasks.

---

## 🎯 Objectives

* Load English and French word embeddings.
* Construct embedding and transformation matrices.
* Learn a linear mapping between two embedding spaces.
* Implement a loss function and gradient calculation.
* Align English word vectors with French word vectors.
* Retrieve translations using nearest-neighbor search.
* Evaluate translation results across a vocabulary.
* Generate document embeddings from tweets.
* Implement vector hashing and hash tables.
* Use LSH for approximate nearest-neighbor search.
* Retrieve tweets with similar vector representations.

---

## 📂 Data

The assignment uses pretrained word embeddings and tweet text.

| Data                      | Purpose                                                           |
| ------------------------- | ----------------------------------------------------------------- |
| English word embeddings   | Represent English words as vectors                                |
| French word embeddings    | Represent French words as vectors                                 |
| English–French word pairs | Support embedding alignment and translation testing               |
| Tweet samples             | Provide text for document-vector generation and similarity search |

The notebook also uses NLTK resources, including the Twitter samples and stopwords datasets.

---

## ⚙️ Methodology

### 1. Word Embedding Matrices

Load English and French word embeddings and construct the matrices needed to learn a transformation between the two vector spaces.

### 2. Translation as a Linear Transformation

Learn a mapping that transforms English word vectors into the French embedding space.

The transformation is optimized using a loss function and gradient-based updates.

### 3. Embedding Alignment

Align the English embeddings with their corresponding French embeddings using the learned transformation matrix.

### 4. Translation with Nearest Neighbors

After mapping an English word vector into the French space, search for the closest French word vector to identify a likely translation.

Evaluate the translation system using the provided vocabulary.

### 5. Document Embeddings

Convert tweets into document vectors by combining the word embeddings of their constituent words.

### 6. Locality Sensitive Hashing

Implement hash functions and hash tables that group similar vectors into candidate search buckets.

LSH enables approximate nearest-neighbor retrieval by narrowing the search to likely candidates.

### 7. Approximate Similarity Search

Use the hash tables to retrieve candidate tweets and identify similar documents without comparing every tweet against every other tweet.

---

## 🔄 Workflow

```text
PART 1: NAIVE MACHINE TRANSLATION

English & French Word Embeddings
              ↓
       Embedding Matrices
              ↓
      Learn Linear Mapping
              ↓
     Loss & Gradient Updates
              ↓
      Align Embedding Spaces
              ↓
       Nearest-Neighbor Search
              ↓
       Translation Evaluation


PART 2: LSH AND DOCUMENT SEARCH

         Tweet Samples
              ↓
       Text Processing
              ↓
      Document Embeddings
              ↓
       LSH Hash Functions
              ↓
          Hash Tables
              ↓
    Approximate Nearest Neighbors
              ↓
        Similar Tweet Search
```

---

## 🧠 Key Concepts

* Word Embeddings
* Vector Space Models
* Cross-Lingual Embeddings
* English–French Translation
* Linear Transformation
* Embedding Alignment
* Loss Function
* Gradient Descent
* Nearest-Neighbor Search
* Cosine Similarity
* Document Embeddings
* Locality Sensitive Hashing (LSH)
* Hash Functions
* Hash Tables
* Approximate Nearest Neighbors
* Semantic Search
* NLP Information Retrieval

---

## 🛠️ Technologies & Tools

* Python
* Jupyter Notebook
* NumPy
* Pandas
* NLTK
* Matplotlib
* Pretrained word embeddings

---

## 📈 Learning Outcomes

By completing this assignment, I practiced:

* Working with pretrained embeddings across languages.
* Learning a linear transformation between embedding spaces.
* Applying nearest-neighbor search to translation.
* Evaluating translation predictions.
* Converting text into document-level vector representations.
* Understanding how LSH reduces the search space for similarity retrieval.
* Implementing hash functions and hash tables.
* Applying approximate nearest-neighbor search to tweet similarity.

---

## 📁 Notebook

`Naive_Machine_Translation_and_LSH.ipynb`

The notebook contains the implementation of embedding alignment, translation testing, document-vector generation, LSH hashing, and approximate nearest-neighbor search.

---

## 📚 Course Information

| Field           | Details                                               |
| --------------- | ----------------------------------------------------- |
| Course          | Classification and Vector Spaces in NLP               |
| Assignment      | Assignment 4 — Naive Machine Translation and LSH      |
| Topics          | Word Embeddings, Translation, LSH                     |
| Main techniques | Linear Mapping, Nearest Neighbors, Approximate Search |
| Environment     | Jupyter Notebook                                      |

---

## 👨‍💻 Purpose

This project is part of my NLP and machine learning portfolio, demonstrating practical understanding of cross-lingual embeddings, vector transformations, semantic similarity, and efficient document retrieval.
