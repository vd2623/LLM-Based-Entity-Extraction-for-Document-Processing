# LLM-Based Entity Extraction for Document Processing

## Overview
This project extracts key entities from legal and financial documents using NLP and fine-tuned Transformer models.

## Features
- Named Entity Recognition (NER) using `spaCy`
- Summarization using `Hugging Face Transformers (BART)`
- Deployable via `FastAPI`

## Installation
```bash
pip install spacy transformers fastapi uvicorn
python -m spacy download en_core_web_sm

