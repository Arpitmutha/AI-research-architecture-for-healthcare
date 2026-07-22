## 📌 Project Overview

**AI Research Copilot for Healthcare** is a domain-specific, multi-agent research assistant designed to streamline scientific literature analysis in medical imaging and healthcare AI. Powered by **IBM watsonx.ai**, **watsonx Orchestrate**, and **Retrieval-Augmented Generation (RAG)**, the copilot enables researchers, clinicians, and students to quickly extract key parameters, compare model architectures, and identify research gaps directly from peer-reviewed papers.

### ✨ Key Features
* 🛡️ **Zero-Hallucination RAG Grounding:** Synthesizes insights strictly from uploaded peer-reviewed literature (*Nature, IEEE, MDPI*).
* 🤖 **Multi-Agent Orchestration (A2A):** Utilizes specialized agents for summarization, comparative analysis, and research gap detection using IBM watsonx Orchestrate.
* 📊 **Automated Literature Matrix:** Automatically extracts model architectures (e.g., CNNs vs. Vision Transformers), modalities (MRI, CT, X-Ray), datasets, and metrics (AUC, Dice score) into structured comparative tables.
* 🔒 **Scientific Guardrails:** Built-in scope enforcement to reject non-healthcare queries and transparently report missing data points.

### 🛠️ Tech Stack
* **Agent Orchestration:** IBM watsonx Orchestrate ADK, Agent-to-Agent (A2A) Protocol
* **LLM Engine & RAG:** IBM watsonx.ai (Granite / Llama 3), LangChain / LlamaIndex
* **Vector Store & Indexing:** Milvus / ChromaDB / IBM Vector Search
* **API Integration:** Python 3.11+, FastAPI, `ibm-watsonx-ai` SDK
