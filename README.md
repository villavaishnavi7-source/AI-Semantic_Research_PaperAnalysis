# AI Semantic Research Paper Analysis Engine

An AI-powered semantic search and research paper analysis engine that retrieves contextually relevant research papers based on meaning rather than exact keyword matching. The system combines Transformer-based semantic embeddings, FAISS indexing, keyword extraction, Named Entity Recognition (NER), and LangChain-powered NLP pipelines to provide intelligent research paper retrieval and analysis.

---

## Features

- Semantic search over research papers using Transformer embeddings
- High-speed similarity search with FAISS indexing
- Context-aware retrieval beyond keyword matching
- Keyword extraction and analysis for important research concepts
- Named Entity Recognition (NER) for title-based analysis of research papers
- Interactive query-based search interface
- Efficient storage and retrieval using pre-computed embeddings
- Top-K research paper recommendation system
- Modular NLP pipeline powered by LangChain and Hugging Face

---

## Tech Stack

### Programming Language
- Python

### NLP & Machine Learning
- Sentence Transformers (`all-MiniLM-L6-v2`)
- Hugging Face Transformers
- Named Entity Recognition (NER)
- Semantic Embeddings
- Keyword Analysis and Extraction
- Natural Language Processing (NLP)

### Frameworks & Libraries
- LangChain
- FAISS (Facebook AI Similarity Search)
- Transformers
- Sentence-Transformers
- NumPy
- Jupyter Notebook

### AI Techniques Used
- Semantic Search
- Vector Embeddings
- Similarity Scoring
- Top-K Information Retrieval
- Keyword Analysis
- Named Entity Recognition (NER)

---

## Project Structure

```text
AI-Semantic_Research_PaperAnalysis/
│
├── CBSOT_project_2 (1).ipynb
├── paper_embeddings.npy
├── paper_faiss.index
├── README.md
└── .gitignore
```

---

## How It Works

1. Load and preprocess the research paper dataset.
2. Generate semantic embeddings using Sentence Transformers and Hugging Face models.
3. Store embeddings as NumPy arrays.
4. Build a FAISS index for efficient vector similarity search.
5. Process the user's query through the LangChain-powered NLP pipeline.
6. Convert the query into semantic embeddings.
7. Retrieve the Top-K most relevant research papers using FAISS similarity search.
8. Perform keyword extraction and analysis on the retrieved papers.
9. Apply Named Entity Recognition (NER) for title-based entity analysis.
10. Display the paper title, abstract, extracted keywords, identified entities, and similarity scores.

---

## Applications

- Academic Search Engines
- Intelligent Research Paper Recommendation Systems
- Literature Review Automation
- Scientific Knowledge Discovery
- NLP-based Document Retrieval Systems
- Research Trend Analysis






---

## Author

**Vaishnavi Vashisht**  
