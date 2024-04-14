
# PDF Chat

PDF Chat is a Python Web app that enables users to upload one or more PDF files and to ask questions, which will be answered by Google's Gemini AI from the content of PDF files.


## Features

- **PDF Upload:** Users can upload one or many PDF files. 
- **Question Answering:** Users can ask questions related to the content of the PDF files.
- **Gemini AI Integration:** PDF Chat uses Google's Gemini AI to provide accurate answers based on the uploaded PDF content.
- **Optimised Text Processing:** It can also handle PDF files with large amount of content.


## Installation

To run PDF Chat Website locally:

1. Clone this repository to your computer.

```bash
  git clone https://github.com/Venkat-737/PDF-Chat.git
```
2. Install the required dependencies from requirements.txt:

```bash
  pip install -r requirements.txt
```
3. Obtain a Google Gemini API Key from [ai.google.dev](https://ai.google.dev/) and set it in a .env file as GOOGLE_API_KEY="Your_API_Key_Here".
4. Run the app using:

```bash
  streamlit run chatpdf1.py
```
## Usage

1. After running app, a web interface will be launched.
2. Upload one or more PDF files and click on the "Submit & Process" button.
3. Enter your question in the given text input field.
4. Press "Enter" to get the answer from Gemini AI.


## Dependencies

- streamlit
  
- google-generativeai
- PyPDF2
- python-dotenv
- langchain
- langchain_google_genai
- faiss-cpu
## API

#### Google Gemini API: 
Used for accessing Google's Generative AI to answer questions based on PDF content.

