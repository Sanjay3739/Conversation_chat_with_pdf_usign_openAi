# Conversation Chat with PDF using OpenAI

This project allows users to interact with PDFs using OpenAI's language models. The PDF content is extracted, and a conversational AI chatbot responds based on the information in the document.

## Features:
- Extracts text from PDF files.
- Interacts with users in natural language.
- Provides answers based on the PDF content.

## Requirements:
- Python 3.x
- OpenAI API key
- PyPDF2 or similar library for PDF parsing

## Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/Sanjay3739/Conversation_chat_with_pdf_usign_openAi.git

2. Create and virtual environment (optional but recommended):   
   ```bash
   python -m venv venv

3. Activate a virtual environment (optional but recommended):
   ```bash
   source venv/bin/activate #for linux
   venv\Scripts\activate #for Windows


4. Install dependencies:
   ```bash
   pip install -r requirements.txt

5. Set your OpenAI API key:
   ```bash
   OPENAI_API_KEY='your-api-key'

6. Run the chatbot:
   ```bash
   python app.py
