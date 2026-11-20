## Hey, I'm Yaashu 👋

**Software & ML Engineer · ML Infrastructure · Distributed Systems · Open Source**

I'm a Computer Science master's student at **Stony Brook University**. I like building systems that are efficient, reliable and useful, and understanding how things work under the hood. My work spans ML infrastructure, distributed data processing, applied machine learning, LLM inference and full-stack development.

I'm currently diving deeper into ML infrastructure by contributing to open-source **LLM inference engines** like vLLM, SGLang and Ray. Fixing real bugs in these codebases is how I'm learning how large-scale model serving works.

📫 Open to **2027 new grad** roles in Software Engineering, ML Engineering, ML Infrastructure and systems.

---

### 🔓 Open Source Contributions

**Merged into [vLLM](https://github.com/vllm-project/vllm)**

| PR | What I fixed |
|---|---|
| [#65935](https://github.com/vllm-project/vllm/pull/65935) | **ROCm MoE kernel benchmark:** the tuning script failed with current Ray on AMD GPUs, and multi-GPU runs could not tell the workers' devices apart. Validated on 2× Radeon RX 9070 XT. |
| [#64885](https://github.com/vllm-project/vllm/pull/64885) | **EmbeddingGemma 2:** every request for shortened (Matryoshka) embeddings was rejected. Enabled the model's supported sizes through its model config hook. |
| [#62517](https://github.com/vllm-project/vllm/pull/62517) | **DeepSeek V4.1 tool parser:** a variant spelling of the tool-call opener leaked into the response text instead of starting a tool call. |
| [#63186](https://github.com/vllm-project/vllm/pull/63186) | **LoRA + speculative decoding:** fixed a regression where draft models blocked LoRA serving. |
| [#61884](https://github.com/vllm-project/vllm/pull/61884) | **LoRA validation:** models without LoRA support now fail at startup with a clear error, instead of later at runtime. |

**In review**

- **vLLM** [#68202](https://github.com/vllm-project/vllm/pull/68202): Humming-quantized checkpoints with unquantized layers crashed at load. Tested end to end on an NVIDIA RTX 8000.
- **vLLM** [#67597](https://github.com/vllm-project/vllm/pull/67597): Gemma 4 chat template left out the empty thought channel after a tool response when thinking is off.
- **vLLM** [#67274](https://github.com/vllm-project/vllm/pull/67274): release Docker image keeps vLLM's OpenTelemetry versions when installing KV connectors.
- **vLLM** [#63141](https://github.com/vllm-project/vllm/pull/63141): fail fast when a pipeline-parallel MTP draft model has no input embedding.
- **SGLang** [#44909](https://github.com/sgl-project/sglang/pull/44909): AMD AITER MoE path applied a correction bias the fake EP dispatch had zeroed.
- **SGLang** [#44560](https://github.com/sgl-project/sglang/pull/44560): reject out-of-vocabulary `stop_token_ids` in both the Python and Rust servers.
- **SGLang** [#46852](https://github.com/sgl-project/sglang/pull/46852): weight-sync selector so speculative draft models survive target weight reloads.
- **SGLang** [#44926](https://github.com/sgl-project/sglang/pull/44926): return a clear 400 for `input_embeds` requests on Gemma 3n / Gemma 4, instead of crashing the server.
- **Ray** [#67445](https://github.com/ray-project/ray/pull/67445): dashboard advertises the host it is actually bound to.

---

### 🔬 Research & Engineering Experience

- **Stony Brook Medicine:** speech-processing and LLM inference pipelines for clinical research, including speaker diarization with Whisper and NVIDIA NeMo, and analysis of 47K+ diaries and 2K+ interviews.
- **Stony Brook University:** full-stack research applications with React, TypeScript and FastAPI, plus data pipelines handling 450M+ observations across ~240K users.
- **Indian Space Research Organisation (ISRO):** Python and PySpark pipelines for multi-terabyte satellite telemetry, focused on anomaly analysis and data quality; cut manual processing by 40%.
- **Dhirubhai Ambani Institute of Technology:** full-stack analytics applications with React, FastAPI and PostgreSQL, used by 5+ business teams; cut manual reporting by 50%.

---

### 🚀 What I'm Working On

- **LLM inference & serving:** fixing bugs in vLLM, SGLang and Ray, especially ROCm, speculative decoding, tool calling and pooling models.
- **AI systems:** LLM-powered applications and agentic workflows (LangGraph, MCP, RAG).
- **Backend & distributed systems:** scalable APIs and performance-oriented services, like a Go API gateway with Redis rate limiting and circuit breakers.

---

### ⚙️ Tech Stack

- **Languages:** Python, Go, C++, Java, TypeScript, JavaScript, SQL, Bash
- **ML & AI:** PyTorch, TensorFlow, JAX, scikit-learn, Hugging Face Transformers, XGBoost, LangGraph, RAG, MCP, FAISS
- **ML Systems & Inference:** vLLM, SGLang, Ray, ROCm, CUDA, ONNX, quantization, model serving, MLflow
- **Backend & Full Stack:** FastAPI, React, Next.js, Node.js, Spring Boot, REST, gRPC, GraphQL, PostgreSQL, MongoDB, Redis
- **Infrastructure & Data:** Linux, Docker, Kubernetes, AWS, GCP, Azure, Spark, PySpark, Kafka, Airflow, GitHub Actions

---

### 📚 Publications

- *Hate-Speech Identification in English and Bengali: Overview of the HASOC Track 2024*, ACM FIRE 2024 (co-author)
- *Enhancing Sentiment Analysis Using CNN: An Evaluative Study of Traditional Models*, JES 2024 (co-author)

---

### 🤝 Connect

Happy to talk about ML infrastructure, LLM inference, distributed systems and open source.

[LinkedIn](https://www.linkedin.com/in/yaashu-dave) · [GitHub](https://github.com/YaashuDave)
