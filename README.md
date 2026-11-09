# Hamidreza Sadeghzadeh

AI/ML engineer focused on building retrieval-augmented and evidence-grounded applications with large language models.

My recent work combines semantic retrieval, agent orchestration, API-backed inference, and practical interfaces for domain-specific AI systems. I am particularly interested in AI/ML engineering roles involving LLM applications, RAG, NLP, and reliable evaluation.

## Featured projects

### [Agentic Legal RAG System](https://github.com/Hamidreza4p/legal-RAG-system)

A Streamlit application for question answering over structured civil-law documents. It supports single-agent, supervisor/worker multi-agent, and metadata-aware hybrid retrieval modes, using FAISS vector stores and configurable OpenAI or Hugging Face models.

Key engineering areas: LangChain, sentence-transformer embeddings, FAISS retrieval, multi-database routing, legal metadata extraction, and RAGAS evaluation.

### [Evidence-Grounded Misinformation Detection](https://github.com/Hamidreza4p/Miss-Information-Detection-System)

A FastAPI and Streamlit system that accepts article URLs or raw claims, retrieves current web evidence with Tavily, and asks a Hugging Face-hosted Llama model for a structured real/fake/uncertain assessment. It includes user accounts, SQLite-backed history and caching, Docker packaging, tests, and Kubernetes deployment manifests.

A 20-claim course-project evaluation reported 80% strict accuracy and 80% coverage, with 100% accuracy on the 16 decisive responses; the repository documents the sample size and reproducibility limits.

Key engineering areas: evidence retrieval, structured LLM output, REST APIs, web-content extraction, persistence, containerization, and cloud deployment artifacts.

## Technical focus

- **LLM and RAG:** LangChain, OpenAI API, Hugging Face Inference, Tavily, RAGAS
- **Retrieval and NLP:** FAISS, sentence-transformers, semantic search, metadata filtering
- **Application engineering:** Python, FastAPI, Streamlit, SQLite, REST APIs
- **Delivery:** Docker, Kubernetes, GitHub Actions workflows, AWS ECR/EC2 deployment artifacts

I value systems that make their data flow, assumptions, and evaluation process visible—not just their final model output.

