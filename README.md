<div align="center">

## Ayush Kuriakose Chacko

</div>

AI/ML Engineer: computer vision, predictive ML, and agentic workflows. B.Tech CS (VIT Chennai). Based in Bengaluru, open to relocation.

Recently wrapped up an apprenticeship at Mercedes-Benz R&D India, where I worked on computer vision, edge deployment, knowledge distillation, and gesture recognition on Jetson Orin. Open to AI/ML Engineer and Data Scientist roles. Currently contributing to open source.

**Projects**

- **[bulkhead](https://github.com/SyN-droMe/bulkhead)** — tool-calling harness for LLM agents, built around one question: when a tool breaks, does it recover, fail honestly, or fail silently? Tested against six real failure modes — 5 of 7 scenarios recovered or failed honestly, 0 uncaught crashes or hangs.
- **[emulsion](https://github.com/SyN-droMe/emulsion)** — interactive map of 3,222 recipes where any two dishes can be routed together, by what they're made of (TF-IDF) or how they're cooked (sentence embeddings), with a slider trading between the two. 98% of dish pairs routeable; [live demo](https://emulsion.ayushkuriakose.workers.dev/), runs entirely in the browser.
- **[shrinkwrap](https://github.com/SyN-droMe/shrinkwrap)** — drop-in Python wrapper that cuts LLM API cost via prompt caching, context summarization, and response caching. ~27% lower cost across Anthropic and AWS Bedrock
- **[ScholarAI](https://github.com/SyN-droMe/ScholarAI)** — RAG pipeline (LangChain + ChromaDB) for research-paper Q&A, with dual LLM backends (Gemini + local LLaMA via Ollama) behind a FastAPI + Streamlit interface.

**Stack**

Python · PyTorch · TensorFlow · LangChain · scikit-learn · Docker · AWS · GCP

**Open source**

Merged:
- **[caveman](https://github.com/JuliusBrussee/caveman/pull/1052)** — `caveman enable <agent>` wired configs to a proxy it never started, causing a silent mid-stream disconnect. Cherry-picked into the maintainer's merge PR [#1055](https://github.com/JuliusBrussee/caveman/pull/1055), authorship preserved.
- **[pizza-bot](https://github.com/pizza-bot-app/pizza-bot/pull/93)** — a truncated top-level turn was reported as success. Added truncation middleware plus a UI notice.
- **[experiential](https://github.com/experientiallabs/experiential/pull/1052)** — named `tool_choice` rejected the synthesized tool-search name.
- **[jevals](https://github.com/openlayer-ai/jevals/pull/2)** — `pii_extra` weakened Presidio redaction and leaked unrelated entity types.
- **[NPC-Forge](https://github.com/gioblu/NPC-Forge/pull/11)** — added two missing intents to the termy dataset, with tests.
- **[Workshop-Finder](https://github.com/chungimungi/Workshop-Finder/pull/1)** — retry handling for flaky homepage fetches.

Open:
- **[smolagents](https://github.com/huggingface/smolagents/pull/2789)** — docs example called `list_models()` with a deprecated argument.
- **[nano-vllm](https://github.com/GeeeekExplorer/nano-vllm/pull/277)** — bare `assert` on KV-cache exhaustion replaced with a clear error, after the issue's suggested fix didn't survive a trace.
- **[jev-ultrafast](https://github.com/browser-use/jev-ultrafast/pull/109)** — hardcoded demo date changed to compute departure at runtime.
- **[headroom](https://github.com/headroomlabs-ai/headroom/pull/3627)** — content router mistook confident HTML for mixed content. Repro before: 2.8% compression, after: 56.7%.
