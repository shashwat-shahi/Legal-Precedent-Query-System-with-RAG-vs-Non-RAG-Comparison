# Legal Precedent Query System with RAG vs Non-RAG Comparison

## README.md

### Description
This project implements a legal precedent query system that compares two approaches for answering legal questions: a Retrieval-Augmented Generation (RAG) system and a traditional non-RAG approach. The system uses the Groq API for language model inference and leverages sentence transformers for semantic similarity matching.

### Key Features
- RAG-based legal precedent retrieval using sentence embeddings
- Comparison between RAG and non-RAG response generation
- Cosine similarity calculation between responses
- Pre-loaded database of 10 legal precedent cases
- Semantic search functionality for relevant case law

### Technical Stack
- Groq API for LLM inference
- Sentence Transformers (all-MiniLM-L6-v2 model)
- scikit-learn for cosine similarity calculations
- NumPy for numerical operations

### Requirements
- Python 3.x
- groq
- sentence-transformers
- scikit-learn
- numpy

### Usage
The notebook demonstrates four key components:
1. Initialization of embeddings for legal precedents
2. Implementation of relevant precedent retrieval
3. Generation of responses using both RAG and non-RAG approaches
4. Comparison of responses with similarity metrics

### Example Queries
The system is tested with various legal queries including:
- Disability accommodation requirements
- Evidence admissibility without warrants
- Contract coercion implications
- Product liability cases