# Advent of Haystack

A collection of Haystack-powered projects based on [Advent of Haystack](https://haystack.deepset.ai/advent-of-haystack). View my original solutions [here](https://github.com/TheMimikyu/adventOfHaystack/tree/b03363f4ad41a21c1152dbdd2dd48a54be82bdef).

## What is Haystack?

[Haystack](https://haystack.deepset.ai/) is an open-source framework by [deepset](https://www.deepset.ai/) for building:
- Production-ready LLM applications
- Retrieval-augmented generative pipelines
- State-of-the-art search systems for large document collections

## Overview

This repository contains 10 projects demonstrating pipeline building with Haystack and integrations with:
- [Weaviate](https://weaviate.io/) - Vector Database
- [AssemblyAI](https://www.assemblyai.com/) - Speech AI
- [NVIDIA](https://build.nvidia.com/explore/discover) - GPU Computing
- [Arize](https://arize.com/) - ML Observability
- [MongoDB](https://mongodb.com/) - Document Database

## Folder Structure

- `/`: Jupyter notebooks containing experiments and implementations

## Projects

### 1. Web Knowledge Retrieval System
- Fetches content from URLs
- Ranks documents by relevance
- Identifies top 10 relevant documents
- Enables seamless querying and answering

### 2. RAG Pipeline with Weaviate
- Implements Retrieval-Augmented Generation with vector database
- Combines vector search with structured filtering
- Stores both objects and vectors efficiently

### 3. Multi-Query Retrieval Pipeline
- Implements custom Haystack component
- Generates multiple queries from single input
- Handles parallel query processing

### 4. Audio Transcription Pipeline
- Integrates AssemblyAI for speech processing
- Performs speech-to-text conversion
- Enables speaker diarization
- Generates responses based on transcriptions

### 5. RAG Development with deepset Studio
- Utilizes UI-based interface of deepset Studio for pipeline creation
- Leverages deployment tools and templates

### 6. NVIDIA Inference Microservice Architecture
- Integrates with NVIDIA inference microservices for ranking and embeddings
- Implements task delegation optimization
- Enables multilingual embedding document grouping

### 7. Intelligent Toy Matching System & LLM Monitoring with Arize Phoenix
- Creates personalized toy recommendations
- Integrates Arize Phoenix for:
    - Real-time performance tracking
    - LLM response evaluation
    - Trace data visualization
    - Quality monitoring dashboards
- Implements automated evaluation pipeline

### 8. Inventory Management Agent with Custom Tools
- Manages inventory tracking system
- Implements RAG-based web search
- Provides price checking functionality
- Enables CRUD operations on inventory
- Uses DuckDuckGo integration for web search
### 9. Self-Reflecting Gift Recommendation System
- Leverages MongoDB Atlas vector search capabilities
- Enhances semantic search using OpenAI embeddings
- Generates personalized gift recommendations via GPT models  
- Implements advanced reasoning with self-reflection
- Streamlines gift metadata management and organization

### 10. Evaluating a RAG Pipeline with EvaluationHarness
- Uses HotpotQA dataset for testing
- Implements multiple evaluation metrics
- Integrates with Hugging Face and OpenAI
- Provides comprehensive pipeline assessment
- Enables model comparison and parameter tuning


