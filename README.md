# Chat PDF with Gemini

A Streamlit-based web application that allows users to chat with PDF documents. The app leverages Langchain, Google Generative AI, and FAISS for efficient document indexing and querying. Users can upload PDF documents, extract their contents, split them into chunks, create embeddings, and then interact with the content by asking questions.

## Features

- **PDF Upload**: Upload multiple PDF documents for processing.
- **Text Extraction**: Extracts text from uploaded PDF documents.
- **Text Chunking**: Splits the extracted text into smaller chunks for easier querying.
- **Conversational Chat**: Ask questions related to the uploaded PDF content.
- **FAISS Indexing**: Creates a vector store for fast similarity searches.
- **Google Generative AI**: Uses the Google Gemini model for generating detailed answers to user questions.

## Requirements

Before running the app, make sure you have the following dependencies installed:

- Python 3.8+
- Streamlit
- PyPDF2
- langchain
- langchain-google-genai
- FAISS
- python-dotenv
- google-generativeai

### Install dependencies

You can install the required dependencies using `pip`. It's recommended to use a virtual environment.

```bash
pip install -r requirements.txt
