
---

# InsightPDF: Conversational Document AI

**InsightPDF** is a Streamlit app that lets you interact with PDF documents through conversational AI, powered by Google's Gemini model. Upload your PDFs, ask questions, and get accurate, context-based answers.

## Features

- **Chat with PDFs**: Use conversational AI to query your PDF files.
- **Multi-PDF Support**: Upload and interact with multiple PDFs at once.
- **Context-Aware Responses**: Get detailed answers based on document content.
- **Fast Search**: Leverage FAISS for efficient text retrieval.
- **User-Friendly Interface**: Simple, intuitive interaction via Streamlit.

## Installation

1. **Clone the Repo**
   ```bash
   git clone https://github.com/yourusername/InsightPDF.git
   cd InsightPDF
   ```

2. **Set Up Environment**
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows: `myenv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure API Key**
   - Create a `.env` file with your Google API key:
     ```
     GOOGLE_API_KEY=your_google_api_key_here
     ```

## Usage

1. **Run the App**
   ```bash
   streamlit run app.py
   ```

2. **Upload PDFs**: Use the sidebar to upload your files.
3. **Ask Questions**: Enter a question to get answers from your PDFs.

## Contributing

Contributions are welcome! Open an issue or submit a pull request.

## License

Licensed under the MIT License.

---