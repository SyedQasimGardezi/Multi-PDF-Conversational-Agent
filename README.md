# Multi-PDF Conversational Agent
## Overview
Multi-PDF Conversational Agent is a web-based application that allows users to interact with and query information from multiple PDF documents. The application provides a conversational interface where users can upload PDFs and ask questions about the content. It integrates several advanced technologies to deliver accurate and contextually relevant responses.

## Features
PDF Upload: Users can upload multiple PDF files for processing.
Text Extraction and Chunking: Extracts and splits text from PDFs into manageable chunks.
Semantic Search: Uses SentenceTransformer to generate embeddings and FAISS for efficient retrieval.
Conversational AI: Incorporates ChatOpenAI for dynamic, context-aware responses.
Interactive Interface: Built with Streamlit for a user-friendly experience.
Technologies Used
Streamlit: For building the web interface.
PyPDF2: For PDF text extraction.
SentenceTransformer: For generating semantic embeddings.
FAISS: For vector-based similarity search.
LangChain: For conversational capabilities.
ChatOpenAI: For providing context-aware responses.
##Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/multi-pdf-conversational-agent.git
cd multi-pdf-conversational-agent
Create and activate a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure you have the necessary environment variables set up. Create a .env file in the root directory and add your environment-specific configurations.

Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py

Upload your PDF documents using the sidebar and click "Process".

Ask questions about the content of your PDFs using the chat interface.


## Contact
For any questions or inquiries, please contact your email address.
