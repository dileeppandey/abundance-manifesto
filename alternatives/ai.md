# Open Alternatives: AI & Cognition

*Language models, image generation, autonomous agents, and AI infrastructure.*

AI is the most consequential new category of tool in decades. If the means of cognition are controlled by a handful of corporations, we risk a new form of feudalism: intelligence as a rental service, sold back to us at whatever price the landlord sets.

This category maps the open-source AI ecosystem — models, tools, and infrastructure that keep the means of cognition in the commons.

---

## Language Models

### [Llama (Meta)](https://llama.meta.com)
**Replaces:** GPT-4, Claude (for self-hosted use cases)  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Meta's open-weight language model family. Not fully open source (weights are open, training code and data are not), but free to download, run locally, and fine-tune. Powers much of the open-source LLM ecosystem. Available in sizes from 1B to 405B parameters.

**Note:** "Open weight" is not the same as fully open source. The weights are free to use with restrictions. See [Mistral](#mistral-ai) and [Falcon](#falcon) for models with more permissive licenses.

**Get involved:** [Download](https://llama.meta.com) · [Llama ecosystem on HuggingFace](https://huggingface.co/meta-llama)

---

### [Mistral AI](https://mistral.ai)
**Replaces:** GPT-4, Claude  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

European AI company releasing models under Apache 2.0 — fully open source, commercially usable with no restrictions. Mistral 7B punches well above its weight class. Mixtral (mixture-of-experts architecture) rivals much larger models at a fraction of the compute cost.

**Get involved:** [Download on HuggingFace](https://huggingface.co/mistralai) · [Contribute](https://github.com/mistralai)

---

### [Falcon (TII)](https://falconllm.tii.ae)
**Replaces:** GPT-4  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Developed by the Technology Innovation Institute in Abu Dhabi. Released under the Apache 2.0 license. One of the first truly open-source large language models to match commercial performance benchmarks.

**Get involved:** [Download on HuggingFace](https://huggingface.co/tiiuae)

---

### [Phi (Microsoft)](https://huggingface.co/microsoft/phi-2)
**Replaces:** GPT-3.5 (for lightweight tasks)  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Small language models (1.3B–3.8B parameters) that perform remarkably well for their size. Designed for on-device use. MIT licensed. Useful for edge deployment where large models are impractical.

**Get involved:** [Download on HuggingFace](https://huggingface.co/microsoft/phi-2)

---

## Local AI Runtimes

### [Ollama](https://ollama.com)
**Replaces:** OpenAI API (for local inference)  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Run open-source language models locally with a single command. Supports Llama, Mistral, Phi, Gemma, and dozens more. MIT licensed. The simplest way to run an LLM on your own hardware — no data leaves your machine.

**Get involved:** [Contribute](https://github.com/ollama/ollama)

---

### [LM Studio](https://lmstudio.ai)
**Replaces:** ChatGPT UI (for local use)  
**Principle:** [I] Radical Openness (partial)  
**Maturity:** Production-ready  

Desktop application for discovering, downloading, and running local LLMs. Free to use. Not fully open source, but enables open-source models to run locally with a polished UI.

---

### [llama.cpp](https://github.com/ggerganov/llama.cpp)
**Replaces:** GPU-dependent inference servers  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

C++ inference engine for LLMs that runs efficiently on CPU. Enables running large language models on laptops and Raspberry Pis with no GPU. The foundation for much of the local AI ecosystem. MIT licensed.

**Get involved:** [Contribute](https://github.com/ggerganov/llama.cpp)

---

## Image Generation

### [Stable Diffusion](https://stability.ai/stable-image)
**Replaces:** Midjourney, DALL-E  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Open-weights image generation model. Runs locally on consumer hardware. Has spawned an enormous ecosystem of fine-tuned models, LoRAs, and tools. The open-source image generation ecosystem (via Automatic1111, ComfyUI, InvokeAI) is significantly more powerful and flexible than any closed alternative.

**Get involved:** [ComfyUI](https://github.com/comfyanonymous/ComfyUI) · [InvokeAI](https://github.com/invoke-ai/InvokeAI)

---

### [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
**Replaces:** Midjourney, Adobe Firefly  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Node-based UI for Stable Diffusion and other open image/video models. Extremely powerful and extensible. Runs locally. The preferred tool for professional workflows using open models.

**Get involved:** [Contribute](https://github.com/comfyanonymous/ComfyUI)

---

## AI Development Infrastructure

### [Hugging Face](https://huggingface.co)
**Replaces:** Closed model APIs  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

The GitHub of machine learning. Open repository for models, datasets, and spaces (hosted demos). Hosts the majority of open-source AI models. The Transformers library (Apache 2.0) is the most widely used library for working with language models.

**Get involved:** [Contribute to Transformers](https://github.com/huggingface/transformers)

---

### [LangChain](https://www.langchain.com) / [LlamaIndex](https://www.llamaindex.ai)
**Replaces:** Closed orchestration layers  
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Open-source frameworks for building applications with language models — RAG pipelines, agents, multi-step reasoning. Both are MIT licensed and work with any model (open or closed).

**Get involved:** [LangChain](https://github.com/langchain-ai/langchain) · [LlamaIndex](https://github.com/run-llama/llama_index)

---

## AI Governance & Safety

### [EleutherAI](https://www.eleuther.ai)
**Principle:** [I] Radical Openness  
**Maturity:** Production-ready  

Nonprofit AI research organization committed to open-source AI. Created GPT-NeoX, GPT-J, and The Pile (open training dataset). Exists explicitly to counterbalance the concentration of AI development in a few large corporations.

**Get involved:** [Contribute](https://github.com/EleutherAI) · [Discord community](https://www.eleuther.ai/get-involved/)

---

*Missing something? [Submit a Pull Request](../CONTRIBUTING.md) to add it.*
