# Zepto Support Assistant

## Overview
The Support Assistant is a Retrieval-Augmented Generation (RAG) based application designed to answer customer questions using Zepto policy documents.

## Files
- supportassisstant.ipynb - RAG implementation and experimentation.
- requirements.txt - Python dependencies required to run the application.
- Dockerfile - Container configuration.
- .dockerignore - Files excluded from the Docker build context.

## Key Capabilities
- Document ingestion
- Text processing
- Document chunking
- Embedding generation
- Vector-based retrieval
- Context-aware question answering
- Retrieval-Augmented Generation (RAG)

## Knowledge Base
The assistant uses Zepto-specific policy documents covering areas such as:
- Delivery
- Returns
- Membership
- Customer support

## Technologies
- Python
- Jupyter Notebook
- LangChain
- Vector database / retrieval
- Embeddings
- Large Language Models
- Docker

## Running the Project
Install the required dependencies:

    pip install -r requirements.txt

Run the notebook:

    jupyter notebook supportassisstant.ipynb

## Docker
Build the Docker image:

    docker build -t zepto-support-assistant .

Run the container:

    docker run -p 8000:8000 zepto-support-assistant
