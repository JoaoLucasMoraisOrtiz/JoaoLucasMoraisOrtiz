# Hi there, I'm João Lucas Morais Ortiz 👋

```
AI Engineer & GenAI Researcher | UNESP & UNICAMP
Focus: Token-Free LMs • Multi-Agent Evals & Self-Play • Grounded Data Agents • SFT & Alignment
```

<p align="left">
  <a href="https://www.linkedin.com/in/jlucasmortiz/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:joao.ortiz@unesp.br"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Mogi%20Gua%C3%A7u%2C%20SP%20--%20Brazil-lightgrey?style=for-the-badge" alt="Location" />
</p>

---

## ⚡ What I Build & Research

I bridge the gap between **foundational AI research** and **production-grade engineering**. My focus is building robust, low-latency, hallucination-free generative AI systems that operate reliably under real-world constraints.

### 🧠 1. Foundational Architecture: Token-Free Language Models (HTF)
- **HTF (Hierarchical Token-Free LM):** First author of a 144M-parameter token-free architecture for Brazilian Portuguese that eliminates fixed BPE subword vocabularies.
- **Morphological CNN & Intra-Word Attention:** Combines multi-scale 1D CNNs (kernels 2–5 with 4,096 filters) with intra-word self-attention and a two-level autoregressive decoder (sequence-level EOS + local character WordDecoder).
- **Extreme Noise & Typo Robustness:** Demonstrates **7× to 19× greater resilience to textual noise (typos)** than standard BPE models (Pythia-160M, GPT-2 PT), retaining **93.8% Cloze accuracy under 10% corruption** (vs. 43.7% for GPT-2). Pre-trained on Carolina, Wikipedia PT, FineWeb-2, and GigaVerbo (200B tokens).
- **Read the Full Paper:** Published research with UNESP & UNICAMP: [`HTF: A Token-Free Language Model with Morphological CNN for Brazilian Portuguese`](papers/HTF_article.pdf).

### 🤖 2. Multi-Agent Systems & Production Evals
- **Self-Play & Thompson Sampling Arena:** Multi-agent negotiation arenas with multi-level cognitive memory (M1/M2/M3), adaptive exploration, and continuous drift monitoring.
- **Rigorous Evaluation:** LLM-as-a-Judge paired evaluation with ablation testing, Elo rating ladders, and frozen rule validation.
- **Autonomous Tool Use:** Multi-turn tool calling, structured state machines, and evaluation frameworks in Python.

### 📊 3. Grounded Data Agents & Information Retrieval
- **Grounded Tabular Analysis:** Streaming tabular analysis agent with **DuckDB**, strict SQL Guard, and per-cell provenance lineage eliminating tabular hallucinations.
- **Deterministic Information Retrieval:** Hybrid retrieval combining BM25F, PageRank/graph algorithms, and AST code skeletonization for low-latency context injection without external API dependencies.

---

## 🛠️ Tech Stack & Tooling

| Domain | Technologies & Frameworks |
|---|---|
| **Foundational & GenAI** | PyTorch, Hugging Face (Transformers, PEFT, TRL, Datasets), Token-Free Architectures, Char-CNNs, LoRA / DoRA, LiteLLM, Ollama |
| **Information Retrieval & Data** | BM25F, Graph Algorithms (NetworkX, PageRank), Hybrid Search, AST Parsers, DuckDB, SQLite (WAL) |
| **Agentic Systems** | Model Context Protocol (FastMCP), Tool Calling, Multi-Agent Evals, LLM-as-a-Judge |
| **Languages** | Python, C++, SQL, TypeScript / JavaScript, Bash |
| **Engineering & Cloud** | FastAPI, Docker, Docker Compose, Linux / Bash, Git, Caddy, PostgreSQL |

---

## 📄 Selected Research Papers

- 📄 **[HTF: A Token-Free Language Model with Morphological CNN for Brazilian Portuguese](papers/HTF_article.pdf)** *(Ortiz, Guilherme, Queiroz, 2026 — UNESP & UNICAMP)*  
  *A 144M token-free architecture with 7×–19× typo robustness over BPE models on Brazilian Portuguese benchmarks.*

---

## 📌 Featured Projects

- 📄 **[HTF-Portuguese-LM](https://github.com/JoaoLucasMoraisOrtiz/htf-portuguese-lm)** — 144M Token-free Language Model with Morphological CNN and intra-word attention for Brazilian Portuguese.
- 🧪 **[LLM-Agent-Arena](https://github.com/JoaoLucasMoraisOrtiz/llm-agent-arena)** — Autonomous multi-agent self-play arena with Thompson Sampling, memory hierarchy, and Elo-based LLM-as-a-Judge evals.
- 📊 **[TableAgent](https://github.com/JoaoLucasMoraisOrtiz/tableAgent)** — Grounded tabular analysis agent with DuckDB streaming, SQL guardrails, and per-cell evidence lineage.
- 🎓 **[deeplearning-PG-FEEC](https://github.com/JoaoLucasMoraisOrtiz/deeplearning-PG-FEEC)** — Advanced Deep Learning implementations from UNICAMP graduate coursework.

---

## 📬 Let's Connect

- **LinkedIn:** [linkedin.com/in/jlucasmortiz](https://www.linkedin.com/in/jlucasmortiz/)
- **Email:** [joao.ortiz@unesp.br](mailto:joao.ortiz@unesp.br)
- **Location:** Mogi Guaçu, SP - Brazil
