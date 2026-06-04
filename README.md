# Smart Learning Companion

Smart Learning Companion is a PDF-based learning assistant that helps users understand and study documents more effectively. The application allows users to upload a PDF and interact with it through various AI-powered learning tools such as chat, summaries, quizzes, flashcards, notes, and glossary generation.

This project was built as part of my learning journey in Generative AI, Retrieval-Augmented Generation (RAG), and Large Language Model applications.

## Features

- Upload and process PDF documents
- Ask questions about the uploaded PDF
- Generate concise document summaries
- Create multiple-choice quizzes with different difficulty levels
- Generate flashcards for quick revision
- Produce exam-oriented study notes
- Extract important terms and generate a glossary

## Technologies Used

- Python
- Gradio
- LangChain
- Ollama
- Qwen3:8B
- ChromaDB
- HuggingFace Embeddings
- Sentence Transformers
- PyPDF

## How It Works

1. The user uploads a PDF document.
2. The text is extracted and divided into smaller chunks.
3. Embeddings are generated for each chunk and stored in ChromaDB.
4. When the user asks a question, the most relevant chunks are retrieved.
5. The LLM generates a response based on the retrieved content.
6. Additional features such as summaries, quizzes, flashcards, notes, and glossary generation are created using the document content.

## Installation

Clone the repository:

```bash
git clone https://github.com/barathwaj-rs/smart-learning-companion.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Pull the Ollama model:

```bash
ollama pull qwen3:8b
```

## Running the Project

Open the notebook in VS Code, Jupyter Notebook, or Jupyter Lab and run all cells.

The Gradio interface will launch locally in your browser.

## What I Learned

Through this project, I gained hands-on experience with:

- Retrieval-Augmented Generation (RAG)
- Vector databases and embeddings
- LangChain workflows
- Local LLM deployment using Ollama
- Building interactive AI applications with Gradio

## Future Improvements

Some features I would like to add in the future:

- Support for multiple PDFs
- Mind map generation
- Citation extraction
- Better quiz and flashcard generation
- Deployment on a cloud platform

## Author

Barathwaj R S

B.Tech – Computer Science and Engineering (AI & Data Science)

## License

This project is licensed under the MIT License.
