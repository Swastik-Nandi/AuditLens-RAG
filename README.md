# AuditLens-RAG 🔍

### The Universal AI Assistant for Chartered Accountancy (ICAI)

**AuditLens-RAG** is a comprehensive Retrieval-Augmented Generation (RAG) system designed to serve as a high-fidelity knowledge partner for CA students across all levels—**Foundation, Intermediate, and Final**. By grounding LLM responses directly in the full suite of official ICAI modules, it eliminates hallucinations and provides precise, level-specific guidance.

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

## 📅 Universal Roadmap
- [x] Initial Repository Setup & Architectural Design
- [ ] **Phase 1: Multi-Level Data Ingestion**
  - Indexing 100+ modules from Foundation, Inter, and Final levels.
- [ ] **Phase 2: Hierarchical Metadata Tagging**
  - Implementing logic to ensure Foundation students don't receive complex Final-level interpretations.
- [ ] **Phase 3: Vector Embedding & Semantic Indexing**
  - Processing thousands of pages into a searchable high-dimensional vector space.
- [ ] **Phase 4: Multi-Domain RAG Pipeline**
  - Specialized retrieval for Law, Taxation, Auditing, and Advanced Accounting.
- [ ] **Phase 5: User Validation**
  - Stress-testing with real-world CA Foundation & Inter exam queries.
