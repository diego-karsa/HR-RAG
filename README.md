# UNDP Policies Scraper and HRM Policies RAG Setup

## UNDP Policies Scraper

### Overview
This Python script scrapes policy documents from the UNDP (United Nations Development Programme) site, focusing on Human Resource Management policies. It downloads relevant DOCX files, converts them to JSON format, and provides statistical analysis on word counts within these documents.

### Features
- Scrapes policy documents from UNDP's policy pages.
- Filters and downloads documents related to Human Resource Management.
- Converts DOCX files to JSON format for easy data handling.
- Calculates statistical information such as minimum, maximum, average word counts, and standard deviation.

### Usage
1. Ensure Python environment is set up.
2. Install required libraries (`requests`, `beautifulsoup4`, `docx`, `json`, `statistics`).
3. Set `base_url` to the desired UNDP policy page.
4. Run the script to scrape, download, convert, and analyze policy documents.

### Dependencies
- Python 3.x
- Libraries: `requests`, `beautifulsoup4`, `docx`

## UNDP HRM Policies RAG (Risk Assessment and Governance)

### Ollama Setup
This script sets up the Ollama AI model for use with policy document analysis.

### Overview
Ollama is configured and utilized for querying insights from policy documents using advanced natural language processing capabilities.

### Features
- Installs Ollama (`v0.1.30`) and sets it up as a global environment variable.
- Initializes HuggingFace embedding models for document analysis.
- Splits documents into manageable chunks and stores them in a ChromaVectorStore for efficient querying.
- Creates indexes for rapid retrieval and query processing.

### Usage
1. Ensure Python environment is set up.
2. Install required libraries (`ollama-index-embeddings-huggingface`, `llama_index.readers.json`, etc.).
3. Set up Ollama model (`OLLAMA_MODEL`) and initialize necessary components.
4. Run the script to prepare documents, set up indexing, and query the model for insights.

### Dependencies
- Python 3.x
- Libraries: `ollama`, `llama-index`, `c
