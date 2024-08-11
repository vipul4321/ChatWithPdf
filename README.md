Chat PDF with Gemini

Overview
The Chat PDF with Gemini app is a Streamlit-based web application that allows users to interact with PDF documents using natural language queries.
The app utilizes advanced language models and embeddings to provide detailed answers based on the content of uploaded PDF files.

Features
PDF Upload: Upload multiple PDF files for processing.
Text Extraction: Extracts and processes text from the uploaded PDFs.
Text Chunking: Splits the extracted text into manageable chunks for efficient querying.
Vector Storage: Utilizes FAISS for indexing and searching text chunks.
Question Answering: Uses Google Generative AI models to provide context-aware answers to user questions.

Technologies Used
Streamlit: For building the web application interface.
PyPDF2: For extracting text from PDF files.
LangChain: For text processing and question-answering.
FAISS: For efficient vector similarity search.
Google Generative AI: For generating contextual answers.

Setup and Installation
Clone the Repository:

git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_DIRECTORY>
Install Dependencies:

Ensure you have Python 3.8 or later installed. Create a virtual environment and install the required packages:


python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
Set Up Environment Variables:

Create a .env file in the root directory of the project with the following content:

GOOGLE_API_KEY=your_google_api_key
Run the Application:

Start the Streamlit app:

streamlit run app.py
Access the App:

Open your browser and navigate to http://localhost:8080 to use the application.
