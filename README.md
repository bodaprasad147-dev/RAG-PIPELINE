# RAG Pipeline for EHR Documents

A complete Retrieval-Augmented Generation (RAG) pipeline for processing Electronic Health Record (EHR) documents using multiple vector databases and embedding strategies.

## Features

- *Document Ingestion*: Upload and process Markdown EHR files (patient demographics, medical history, vitals, labs)
- *Three Chunking Strategies*: Fixed-size, sliding window, semantic chunking
- *Multi-Embedding Support*: gte-Qwen2-1.5B, e5-large-v2, bge-m3 models
- *Vector Database Integration*: Chroma Cloud, Pinecone, Weaviate Cloud
- *LLM Generation*: Groq API with context-bound prompting

## Pipeline Overview

## Quick Start

1. *Set Environment Variables*
bash
export CHROMA_API_KEY="your_key"
export PINECONE_API_KEY="your_key"
export WEAVIATE_UR…
