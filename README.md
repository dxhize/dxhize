# Hi, I'm Dxhize. 👋

I’m an ECE undergraduate focused on low-level systems engineering, mathematical optimization, and building efficient software from first principles.

## About Me

I enjoy working at the intersection of systems, algorithms, and performance. My interests sit around:

- low-level memory behavior and hardware-aware design
- embedded systems and real-time constraints
- signal processing and numerical reasoning
- algorithm optimization and software efficiency

## Workstation & Stack

- **OS:** Fedora Linux
- **Languages:** C, Python
- **Focus Areas:** algorithm optimization, embedded systems, signal processing, systems design

## Current Focus

- 🎓 progressing from **CS50p** to **CS50x** to deepen my understanding of memory layout and low-level engineering
- 📐 strengthening calculus and linear algebra to improve performance reasoning and numerical rigor
- 🎯 aiming to contribute to open-source projects and pursue opportunities in GSOC 2027

## Featured Project

### Deep Researcher

I was the primary builder of [Deep Researcher](https://github.com/Deep-researcherr/deep-researcher), an agentic research system designed to plan queries, gather evidence from multiple sources, validate findings, and produce structured research outputs with traceable citations.

This project reflects the kind of systems work I enjoy most: combining architecture, modeling, retrieval, and user-facing execution into one coherent pipeline.

I also collaborated closely with **@chiraglaheru** on the project as a co-developer, contributing to backend integration, system design, and project-level engineering decisions.

### What I built

- **Core research pipeline architecture**: designed the LangGraph-based orchestration for planning, search, evidence collection, and synthesis
- **Retrieval and parsing layer**: implemented resilient document fetching across PDFs, GitHub repos, arXiv papers, patents, and multi-source search results
- **Evidence validation**: built quote-verified extraction, ranked findings by quality, and added contradiction detection to keep outputs grounded in retrieved material
- **LLM reliability**: engineered fallback logic, rate-limit handling, request pacing, and provider health tracking for robust operation under constrained API budgets
- **Frontend experience**: created a real-time streaming interface for progressive results, source exploration, and methodology inspection
- **Testing and verification**: structured a strong validation layer to maintain reliability across core pipeline stages

### Why it matters

Deep Researcher is more than a chatbot wrapper — it is a research engine built around evidence quality, retrieval discipline, and system resilience. The architecture emphasizes grounded reasoning instead of shallow summarization, which makes it a strong example of my systems and software engineering approach.

### Stack

- **Backend:** Python, FastAPI, LangGraph, Pydantic
- **Search:** SerpApi (web, news, scholar, GitHub, patents)
- **Models:** litellm with multi-provider support
- **Frontend:** HTML, CSS, JavaScript, SSE streaming
- **Testing:** pytest, pipeline validation, resilience checks

[View the project →](https://github.com/Deep-researcherr/deep-researcher)
