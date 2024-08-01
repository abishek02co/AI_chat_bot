# CSV Chat Application

This Streamlit application allows users to chat with their CSV data using a language model. It provides an interactive interface for uploading CSV files and querying the data using natural language.

## Features

- Upload CSV files
- Chat interface for querying CSV data
- Utilizes FAISS for efficient similarity search
- Powered by the Llama 2 language model


## Installation

1. Clone this repository
2.  Install the required packages:streamlit
streamlit-chat
langchain
faiss-cpu
sentence-transformers
ctransformers

3. Download the Llama 2 model file (`llama-2-7b-chat.ggmlv3.q8_0.bin`) and place it in the project directory.

## Usage

Run the Streamlit app:

Then, open your web browser and go to the URL provided by Streamlit.

## How it works

1. Upload a CSV file using the sidebar.
2. The app processes the CSV data and creates a vector store using FAISS.
3. Use the chat interface to ask questions about your data.
4. The app uses a conversational retrieval chain to generate responses based on your queries.

## Built by

Prince Vegeta 🕸️

## License

[MIT License](LICENSE)
