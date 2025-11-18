# 🤖 RAG Assistant

> **A modular Retrieval-Augmented Generation (RAG) pipeline for document search, chunking, embedding, and conversational AI.**

<p align="center">
  <img src="https://raw.githubusercontent.com/MansurPro/RAG-assistant/main/assets/custom-commands/rag-visual.png" alt="RAG Assistant Visual" width="600"/>
</p>

---

## 🚀 Features

- **Document Ingestion:** Flexible ingestion for markdown, text, and more.
- **Chunking:** Smart document chunking for optimal retrieval.
- **Embeddings:** Integrates with state-of-the-art embedding models.
- **Vector Search:** Fast, scalable semantic search using ChromaDB.
- **Conversational Engine:** Chat interface for natural language queries.
- **Extensible:** Modular core for easy customization and extension.

---

## 🗂️ Folder Structure

```text
ai-tech-rag/
├── assets/                # Visuals, custom commands, and static assets
├── chroma_db/             # ChromaDB vector database files
├── qwerty/                # Python virtual environment
├── rag-assistant/         # Main app and core modules
│   ├── app.py             # Flask app entry point
│   ├── core/              # Core RAG logic (chat, vector, document)
│   ├── static/            # Frontend static files (CSS, JS)
│   └── templates/         # Jinja2 HTML templates
├── techcorp-docs/         # Example documents for ingestion
├── test_*.py              # Unit and integration tests
├── requirements.txt       # Python dependencies
└── README                 # This file
```

---

## 🛠️ Quickstart

```bash
# 1. Clone the repo
git clone https://github.com/MansurPro/RAG-assistant.git
cd ai-tech-rag

# 2. Create and activate a virtual environment (optional)
python3 -m venv qwerty
source qwerty/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python rag-assistant/app.py
```

---

## 💡 Usage

1. **Ingest Documents:**
	- Place your files in `techcorp-docs/` or use `ingest_documents.py`.
2. **Search & Chat:**
	- Use the web UI at [http://localhost:5000](http://localhost:5000) to chat and search.
3. **Test the Pipeline:**
	- Run `pytest` or use the provided test scripts.

---

## 🌐 Visual Overview

<p align="center">
  <img src="https://raw.githubusercontent.com/MansurPro/RAG-assistant/main/assets/custom-commands/rag-pipeline-diagram.png" alt="RAG Pipeline Diagram" width="700"/>
</p>

---

## 📦 Key Modules

- `core/document_processor.py` – Document loading, chunking, and preprocessing
- `core/vector_engine.py` – Embedding and vector search logic
- `core/chat_engine.py` – Conversational AI and retrieval logic
- `app.py` – Flask app and API endpoints

---

## 🧪 Testing

```bash
pytest
# or run individual test files, e.g.
python test_chunking.py
```

---

## 🤝 Contributing

Pull requests and issues are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

MIT License. See `LICENSE` for details.
