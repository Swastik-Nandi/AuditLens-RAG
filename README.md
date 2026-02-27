# AuditLens-RAG 🔍

### Specialized AI for Indian Taxation & Auditing

**AuditLens-RAG** is a Retrieval-Augmented Generation (RAG) system designed to solve the "Hallucination Problem" in general-purpose LLMs when dealing with complex Indian financial regulations. By grounding responses directly in official ICAI (Institute of Chartered Accountants of India) modules, it ensures professional-grade accuracy.

---

## 🎯 The Problem
General AI models (like ChatGPT) often struggle with the specific nuances of the Indian Finance Act, often mixing up tax slabs or outdated auditing standards. This leads to confident but incorrect financial advice.

## 💡 The Solution
AuditLens uses a "Grounding" architecture:
1. **Source Retrieval:** The system scans official ICAI PDF modules for the specific query.
2. **Contextual Injection:** Only relevant clauses and sections are fed to the LLM.
3. **Verified Output:** Every answer includes a citation back to the specific document and page number.

## 🛠️ Planned Tech Stack
- **Language:** Python
- **Orchestration:** LangChain
- **Vector Database:** ChromaDB / FAISS
- **Data Source:** ICAI Board of Studies (BoS) Knowledge Portal

## 📅 Project Roadmap
- [x] Initial Repository Setup & Architectural Design
- [ ] Data Ingestion: Processing Income Tax & Auditing PDF modules
- [ ] Vector Embedding: Creating a semantic search index
- [ ] RAG Pipeline: Implementing grounded response logic
- [ ] Evaluation: Hallucination testing against edge-case tax queries
