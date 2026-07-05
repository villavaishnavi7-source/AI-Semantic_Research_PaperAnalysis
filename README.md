AI Semantic Research Paper Analysis Engine

An AI-powered semantic search and research paper analysis system that retrieves contextually relevant research papers based on meaning rather than exact keyword matching. The project leverages Transformer-based sentence embeddings, FAISS vector indexing, keyword extraction, Named Entity Recognition (NER), abstractive summarization, and explainable semantic recommendations to enable intelligent research paper discovery and analysis.

---

Features

- Semantic search over Machine Learning research papers using Transformer embeddings
- Retrieval of contextually similar papers beyond exact keyword matching
- High-speed vector similarity search using FAISS indexing
- Cosine similarity-based ranking of research papers
- Automatic generation and storage of embeddings for efficient retrieval
- Keyword extraction using KeyBERT for identifying important research concepts
- Named Entity Recognition (NER) using BERT for title and abstract analysis
- Abstractive summarization of research paper abstracts using BART
- Explainable semantic recommendations by highlighting concepts shared between the query and retrieved papers
- Top-K research paper recommendation system
- Modular NLP pipeline with LangChain integration

---

Dataset

- Dataset: "CShorten/ML-ArXiv-Papers"
- Source: Hugging Face Datasets
- Papers Used: First 15,000 Machine Learning research papers
- Data Fields:
  - Title
  - Abstract
  - Combined Paper Text (Title + Abstract)

---

Tech Stack

Programming Language

- Python

NLP & Deep Learning Models

- Sentence Transformers ("all-MiniLM-L6-v2")
- Hugging Face Transformers
- BART ("facebook/bart-large-cnn")
- BERT-based Named Entity Recognition ("dslim/bert-base-NER")
- KeyBERT

Libraries & Frameworks

- Pandas
- NumPy
- Scikit-learn
- FAISS (Facebook AI Similarity Search)
- Transformers
- Sentence-Transformers
- LangChain
- Hugging Face Datasets
- Jupyter Notebook / Google Colab

---

AI Techniques Used

- Semantic Search
- Sentence Embeddings
- Vector Similarity Search
- Cosine Similarity Scoring
- Top-K Information Retrieval
- Keyword Extraction and Analysis
- Named Entity Recognition (NER)
- Abstractive Text Summarization
- Explainable AI (XAI) for Semantic Recommendations

---

Project Workflow

1. Load the "ML-ArXiv-Papers" dataset from Hugging Face.
2. Extract paper titles and abstracts.
3. Create a combined paper representation by concatenating the title and abstract.
4. Preprocess and clean the text data.
5. Generate semantic embeddings using the "all-MiniLM-L6-v2" Sentence Transformer model.
6. Store embeddings as NumPy arrays for reuse.
7. Normalize embeddings and create a FAISS vector index.
8. Convert user queries into semantic embeddings.
9. Retrieve the Top-K most relevant research papers using cosine similarity search.
10. Generate summaries of retrieved paper abstracts using BART.
11. Extract important keywords and key phrases using KeyBERT.
12. Perform Named Entity Recognition using BERT-based NER models.
13. Provide explainable recommendations by identifying shared concepts between the query and retrieved papers.

---

Project Structure

AI-Semantic_Research_Paper_Analysis/
│
├── CBSOT_project_2.ipynb
├── paper_embeddings.npy
├── paper_faiss.index
├── README.md
└── .gitignore

---

Example Query

query = "deep learning for medical image analysis"

Output Includes

- Research Paper Title
- Similarity Score
- Paper Abstract
- Generated Summary
- Extracted Keywords
- Named Entities
- Explanation of Why the Paper Was Recommended

---

Applications

- Semantic Academic Search Engines
- Intelligent Research Paper Recommendation Systems
- Literature Review Automation
- Scientific Knowledge Discovery
- NLP-based Document Retrieval Systems
- Research Trend Analysis
- AI-assisted Research Exploration Platforms

---


Author

Vaishnavi Vashisht

