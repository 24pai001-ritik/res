# Paper Explainer Pro

A Streamlit application to analyze, summarize, and chat with research papers using Google Gemini and RAG.

## Features
- **PDF Upload**: Upload one or two papers.
- **Summarization**: Get TL;DR, glossary, and key contributions.
- **Deep Dive**: Explain specific sections (Abstract, Methodology, etc.).
- **Chat**: Ask questions about the paper using RAG (Retrieval Augmented Generation).
- **Comparison**: Compare two papers side-by-side.
- **Research Gap**: Identify potential research gaps.
- **Export**: Download notes as Markdown or DOCX.

## Local Installation

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run res.py
   ```

## Deployment on Streamlit Cloud

1. **Push to GitHub**: Ensure this code is in a public or private GitHub repository.
2. **Sign in to Streamlit Cloud**: Go to [share.streamlit.io](https://share.streamlit.io/) and sign in with GitHub.
3. **Deploy**:
   - Click "New app".
   - Select your repository, branch, and the main file path (`res.py`).
   - Click "Deploy".
4. **API Key**:
   - Once deployed, the app will ask for the Gemini API Key in the sidebar.
   - You can get your key from [Google AI Studio](https://aistudio.google.com/).

## Requirements
- Python 3.8+
- A Google Gemini API Key
