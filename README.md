# TDS Project May‑2025 DATA with working on locally project!!

This repository contains your **TDS Content**, **TDS Project May‑2025** modules, and relevant scripts developed during May 2025. It is meant to serve as a comprehensive collection of your learning artifacts, code, and extracted content—excluding the working version and Vercel deployment-specific files.

---

## 📁 Project Structure

```

.
├── TDS Content
│   ├── GA 1/
│   │   ├── Question 10/11/12/14/
│   │   │   └── python.py
│   │   ├── Question 3/
│   │   │   └── uv.txt
│   │   ├── Question 7/
│   │   │   └── hidden.txt
│   │   └── Question 8/
│   │       └── python.py
│   │   └── README.md
│   ├── GA 2/
│   │   ├── Question 1/
│   │   │   └── answer.txt
│   │   ├── Question 10/
│   │   │   ├── Readme‑for‑steps.md
│   │   │   ├── main.py
│   │   │   ├── q‑fastapi.csv
│   │   │   └── requirements.txt
│   │   ├── Question 2/
│   │   │   ├── image.webp
│   │   │   └── steps.md
│   │   ├── Questions 3‑9/
│   │   │   └── steps.md per question
│   │   └── Question 6/
│   │       ├── README.md
│   │       ├── api/index.py
│   │       ├── api/vercel‑data.json
│   │       ├── requirements.txt
│   │       └── vercel.json
│   ├── GA 3/
│   │   ├── Question 1‑14 with .md, .py, .js, .yaml as required
│   │   └── README.md
│   ├── GA 4/ … GA 7/
│   ├── LICENSE.txt
│   ├── Pre‑requisites/linux.md
│   ├── Project 1 M25/
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── app/embed.py
│   │   ├── app/index.py
│   │   ├── app/rag.py
│   │   ├── automation\_script\_md\_to\_json\_format.py
│   │   ├── promptfoo.yaml
│   │   └── requirements.txt
│   ├── README.md
│   └── question.sh
├── TDS Project May‑2025/
│   ├── Md to Metadata covertor/
│   │   ├── automation\_script\_md\_to\_json\_format.py
│   │   ├── tds\_content.json
│   │   └── tds\_pages\_md/ (metadata markdown files)
│   ├── Project 1 (Not Ideal for vercel)/
│   │   ├── LICENSE
│   │   ├── README.md
│   │   ├── embed.py
│   │   ├── index.py
│   │   ├── rag.py
│   │   ├── rag\_pipeline.py
│   │   ├── promptfoo.yaml
│   │   ├── requirements.txt
│   │   ├── data/
│   │   │   ├── embeddings.npy
│   │   │   └── metadata.json
│   │   ├── vector\_store.faiss
│   │   └── vercel.json
│   ├── TDS Project Data Downloader and Extractor/
│   │   ├── discourse\_downloader\_full.py
│   │   ├── discourse\_downloader\_single.py
│   │   ├── discourse\_json/
│   │   ├── tds\_pages\_md/
│   │   ├── metadata.json
│   │   └── website\_downloader\_full.py
│   ├── railway.json
│   └── readme.md
└── markdownchecke.py

````

---

## 🧠 Overview & Purpose

- **TDS Content/**: Contains exercise responses (GA 1–GA 4), code demonstrations, and markdown-generated outputs from each question, you can find this in repo named as : TDS Assignments all Weeks
- **Project 1 M25/**: A containerized version of your RAG pipeline with code, embeddings, and data setup for Project 1.
- **TDS Project May‑2025/**: Core modules for content conversion, embedding generation, and extraction tooling.
  - **Md to Metadata convertor/**: Python script and content files to transform markdown into structured JSON.
  - **Project 1 (Not Ideal for vercel)/**: Lightweight version of the RAG pipeline—optimized for local testing.
  - **TDS Project Data Downloader and Extractor/**: Downloads TDS forum content, cleans it into markdown/JSON for indexing.

---

## 🚀 Getting Started

Clone the repo:

```bash
git clone <repo-url>
cd <repo-dir>
````

### Dependencies

Install dependencies for each submodule:

```bash
cd "TDS Project May‑2025/Md to Metadata covertor"
pip install -r requirements.txt

cd "../Project 1 (Not Ideal for vercel)"
pip install -r requirements.txt

cd "../TDS Project Data Downloader and Extractor"
pip install -r requirements.txt
```

### Primary Workflow

1. **Download content** using the extractor script in *TDS Project Data Downloader and Extractor*.
2. **Convert markdown to JSON** via *Md to Metadata covertor*.
3. **Run your RAG logic** in the *Project 1* folder for embedding, vector store building, and query handling.

---

## 📌 Exclusions & Notes

* Excludes the full working app with large binaries and `.git` metadata.
* Large files (like `.npy`, `.faiss`, CSVs, etc.) are ignored via `.gitignore`.
* Optionally track only specific JSON or CSV files using `!filename.json` syntax if needed.

---

## 📄 License

Each subfolder (where applicable) includes its **MIT license** (e.g., `LICENSE`, `LICENSE.txt`). Refer to the specific subfolder for details.

---

## 🙋 Need Help?

If you'd like specific help—like sub-readmes per GA folder or README for **Project 1 (Not Ideal for vercel)**—just let me know!

