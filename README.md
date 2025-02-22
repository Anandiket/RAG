# RAG-Based Chatbot for Academic & NLI Document Assistance

## Introduction
This project implements a **Retrieval-Augmented Generation (RAG) chatbot** using **LangChain** and **Meta Llama 3**, designed to assist:
**University Students** – Helps in exam preparation by leveraging study materials, reference books, syllabus, and past question papers to generate contextual responses, summaries, and notes.

The chatbot uses **PDF text extraction** and **Gemini API for response generation**. The web interface is built using **Streamlit, HTML5, CSS3, and JavaScript**.

## Features
- **RAG-based Response Generation**: Retrieves relevant content from provided PDFs and enhances response quality.
- **Multi-PDF Support**: Handles multiple PDFs for research or academic assistance.
- **Natural Language Processing**: Provides context-aware answers.
- **Real-time Data Handling**: Fetches relevant study material on demand.
- **Summarization & Note Generation**: Automatically generates concise summaries for specific topics.
- **Web-Based Interface**: Interactive UI for seamless user interaction.

---

## Getting Started
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/rag-chatbot.git
cd rag-chatbot
```

### 2. Set Up a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Set Up Environment Variables
Create a `.env` file and add:
```ini
GEMINI_API_KEY=your_gemini_api_key
```

### 5. Run the Application
```bash
streamlit run trail1.py
```
or
```bash
streamlit run multiligual.py # For multilingal chatbox
```
The application will be available at `http://localhost:8501/`.

---

## Requirements
Ensure you have the following installed:
- **Python 3.8+**
- **LangChain**
- **PyMuPDF (fitz) for PDF extraction**
- **Streamlit**
- **Gemini API access**

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## Future Enhancements
- **User Authentication** for personalized interactions.
- **Integration with Google Drive & OneDrive** for document uploads.

---

## Contributing
Feel free to open issues and pull requests to improve this project!

---
## Contact
For queries or collaborations, reach out via [anandiket24@gmail.com](mailto:anandiket24@gmail.com).

