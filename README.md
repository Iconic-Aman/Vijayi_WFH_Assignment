# 🚀 Quote Search App with Streamlit + FAISS

This project lets users search quotes using natural language (e.g., _"Show me quotes about courage"_). It uses sentence-transformer embeddings (`all-MiniLM-L6-v2`) for semantic search and displays the results in a user-friendly Streamlit interface.

---

### Video: Below is the video recording about the project 
[Project Demonstration using Loom](https://www.loom.com/share/139be5a4f85843daa7bf1856c26bb0cb?sid=46454b48-57d1-4b06-b2c2-b9922373b8e9)


## 🔧 Tech Stack

- 🧠 Sentence Embeddings: `all-MiniLM-L6-v2` (via `HuggingFaceEmbeddings`)
- 🗃️ Vector Store: FAISS (for similarity search)
- 🌐 UI: Streamlit
- 📡 Deployment: LocalTunnel (Colab compatible)

---

## 📦 Setup

### 1. Install requirements

```bash
pip install -r requirements.txt
```


### 2. Prepare Data

Each quote is turned into a `Document` with metadata (quote, author, tags), and embedded


### 3. Build & Save Vector Index

### 4. Run Streamlit App
```
streamlit run app.py
```

### 5. Expose with LocalTunnel (Colab-friendly)
```
!npx localtunnel --port 8501
```

🙌 Acknowledgements

    HuggingFace Sentence Transformers

    LangChain

    FAISS

    Streamlit

    LocalTunnel (for public URLs in Colab)

