# Quantum Rosette - Chat with PDF (Gemma 3)

A premium, locally hosted "Chat with PDF" application using **Streamlit**, **Ollama**, and **Gemma 3:4b**.

## Features
- **Local AI**: Runs entirely on your machine using Ollama.
- **Gemma 3:4b**: Powered by Google's latest Gemma 3 model.
- **PDF Intelligence**: Extract and query text from any PDF document.
- **RAG Implementation**: Uses local text extraction and context-aware prompting.
- **Modern UI**: Sleek dark mode interface with responsive animations.
- **Demo Mode**: One-click "Load Demo PDF" to test functionality instantly.

## Prerequisites
1. **Ollama**: Install from [ollama.com](https://ollama.com/).
2. **Gemma 3**: Pull the model by running:
   ```bash
   ollama pull gemma3:4b
   ```

## Setup & Installation
1. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Start the Streamlit application:
   ```bash
   streamlit run streamlit_app.py
   ```
2. Open your browser to the URL shown in the terminal (usually `http://localhost:8501`).
3. **Upload a PDF** using the sidebar or click **"Load Demo PDF"** to use the sample file.
4. Ask questions in the chat box!

## File Structure
- `app/main.py`: Main Streamlit application code.
- `data/sample.pdf`: A sample document for demonstration.
- `requirements.txt`: Python dependencies.
- `README.md`: Project documentation.
