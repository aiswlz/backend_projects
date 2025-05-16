# Kazakhstan Constitutional AI Assistant

An AI-powered assistant for answering questions about the Constitution of Kazakhstan, built with Streamlit, LangChain, and Ollama.

## Features

- Document processing for PDF and DOCX files
- Chat interface for constitutional questions
- Source citation for answers
- Conversation history logging
- Ollama LLM integration

## Usage

### Prerequisites

- Python 3.8+
- Ollama server running locally
- Required models downloaded (e.g., llama2, nomic-embed-text)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/kazakhstan-constitution-assistant.git
cd kazakhstan-constitution-assistant

Install dependencies:

bash
pip install -r requirements.txt
Download required Ollama models:

bash
ollama pull llama2
ollama pull nomic-embed-text
Running the Application
bash
streamlit run app.py
Screenshots
Application Screenshot

Examples
Upload the Constitution document (PDF/DOCX)

Process the document

Ask questions like:

"What are the fundamental rights guaranteed by the Constitution?"

"Explain the presidential election process"

"What does Article 1 say about sovereignty?"
