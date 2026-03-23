# Document Intelligence Pipeline

A tool for processing, categorizing, and searching through PDF documents and images using machine learning and OCR. This project explores automated document understanding by building a pipeline that extracts, structures, and makes unstructured document data searchable.

## Key Features
*   Automated text extraction from PDFs and images using OCR (Tesseract).
*   ML-powered categorization and entity extraction from document content.
*   Semantic search capabilities over processed document collections.
*   End-to-end pipeline from raw document ingestion to queryable knowledge base.

## Tech Stack
Python, Tesseract OCR, Scikit-learn, Sentence Transformers, FAISS, Streamlit

## Getting Started
```bash
git clone https://github.com/zoreanuj/document-intelligence-pipeline.git
cd document-intelligence-pipeline
pip install -r requirements.txt
python app.py
```