# Hi, I'm Dxhize. 👋
I am an ECE undergraduate focusing on low-level systems engineering, mathematics, and building optimized software from first principles. 

## 🛠️ Tech Stack & Workstation
- **OS:** Fedora Linux (Daily Driver)
- **Languages:** C, Python
- **Core Interests:** Algorithm Optimization, Embedded Systems, Signal Processing

## 📈 Current Milestones
- 🎓 Transitioning from **CS50p** to **CS50x** to master low-level memory layout.
- 📐 Reviewing calculus and linear algebra to optimize code execution efficiency.
- 🎯 Target: Contributing to open-source organizations in GSOC 2027.

## 🚀 Featured Project: Deep Researcher

I built the majority of the [Deep Researcher](https://github.com/Deep-researcherr/deep-researcher) project and drove the core implementation behind its research pipeline.

### What I contributed
- **Core system architecture**: designed and implemented the LangGraph-based multi-stage research workflow, including planning, parallel search, evidence gathering, and final synthesis.
- **Retrieval pipeline**: built resilient document fetching and parsing across multiple sources, including PDFs, GitHub repositories, arXiv papers, patents, and search results.
- **Evidence analysis**: implemented quote-verified extraction, quality ranking, contradiction detection, and dimension-aware evaluation to keep results grounded in retrieved evidence.
- **LLM resilience**: engineered fallback logic, rate-limit handling, model health tracking, and request pacing to make the system reliable with free-tier providers.
- **Frontend & streaming UX**: built the real-time SSE-driven interface for progressive report updates with source and methodology views.
- **Quality & testing**: developed a strong test suite and validation strategy to ensure the pipeline remains stable and predictable.

### Why it matters
This project is a serious systems engineering effort: it combines retrieval, multi-model orchestration, deterministic evidence handling, and user-facing streaming into a single end-to-end research agent.

### Stack
- **Backend:** Python, FastAPI, LangGraph, Pydantic
- **Search:** SerpApi (web, news, scholar, GitHub, patents)
- **Models:** litellm with multi-provider support
- **Frontend:** HTML, CSS, vanilla JavaScript, SSE
- **Testing:** pytest with comprehensive pipeline and resilience coverage

[View the project →](https://github.com/Deep-researcherr/deep-researcher)
