# 🤖 Self-Hosted Local AI RAG System (n8n + Qdrant + Ollama)

An end-to-end local Retrieval-Augmented Generation (RAG) agent that ingests documents into a vector database and answers queries locally using Ollama and Qdrant via n8n workflow automation.

## 🌟 Key Features
- **Zero Cloud Costs:** Runs 100% locally on system hardware.
- **Data Ingestion Pipeline:** Splits text documents, generates vector embeddings via `nomic-embed-text`, and indexes them inside Qdrant.
- **AI Agent Execution:** Uses `llama3.2` as an interactive chat model connected to Qdrant vector retrieval tools.
- **Privacy First:** Sensitive data never leaves your local machine.

## 🛠️ Tech Stack
- **Workflow Automation:** n8n
- **Vector Database:** Qdrant
- **Local LLM Engine:** Ollama (`llama3.2`, `nomic-embed-text`)
- **Containerization:** Docker Compose
- **Tunneling:** ngrok

