<div align="center">

# 🤗 LLM & HuggingFace — A Complete Learning Journey

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![HuggingFace](https://img.shields.io/badge/🤗%20Transformers-4.x-yellow)](https://huggingface.co/transformers/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Chapters](https://img.shields.io/badge/Chapters-12-purple)](.)
[![Status](https://img.shields.io/badge/Status-Active%20Learning-brightgreen)]()

> **A structured, hands-on study of Large Language Models (LLMs) and the HuggingFace ecosystem** — following the official [Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/), with annotated notebooks, experiments, and personal implementations across 12 comprehensive chapters.

</div>

---

## 👤 About Me

Hi, I'm **Shivanshu Shukla** — a Computer Science student with a deep passion for Natural Language Processing, Large Language Models, and AI systems. This repository documents my structured self-learning journey through the HuggingFace NLP course and beyond, covering everything from the fundamentals of transformer architectures to fine-tuning state-of-the-art language models and building reasoning-capable AI systems.

I'm actively seeking **internship opportunities** in:
- 🧠 Machine Learning / Deep Learning
- 💬 NLP / Conversational AI
- 🤗 AI/LLM Engineering
- 📊 Data Science & AI Research

> 📬 Feel free to connect or reach out via [GitHub](https://github.com/shivanshu1512)!

---

## 🎯 What This Repository Covers

This repo is a **complete, structured walkthrough** of Large Language Models and the HuggingFace ecosystem. Each chapter contains:

- 📓 **Jupyter Notebooks** with clean, well-commented code
- 🧪 **Hands-on experiments** and model outputs
- 📝 **My own notes and insights** on key concepts
- 🔗 **References** to papers, docs, and blog posts

---

## 📚 Table of Contents

| # | Chapter | Topics Covered | Status |
|---|---------|----------------|--------|
| 01 | [🔄 Transformer Models](#chapter-01--transformer-models) | Architecture, Attention, BERT, GPT | ✅ Done |
| 02 | [🤗 Using Transformers](#chapter-02--using-transformers) | Pipelines, Tokenizers, Models API | ✅ Done |
| 03 | [🎯 Fine-Tuning a Pretrained Model](#chapter-03--fine-tuning-a-pretrained-model) | Training Loop, Trainer API, Metrics | 🔄 In Progress |
| 04 | [🚀 Sharing Models and Tokenizers](#chapter-04--sharing-models-and-tokenizers) | HuggingFace Hub, Model Cards | 🔄 In Progress |
| 05 | [📦 The 🤗 Datasets Library](#chapter-05--the--datasets-library) | Loading, Processing, Streaming | 🔄 In Progress |
| 06 | [🔤 The 🤗 Tokenizers Library](#chapter-06--the--tokenizers-library) | BPE, WordPiece, Fast Tokenizers | 📋 Planned |
| 07 | [📋 Classical NLP Tasks](#chapter-07--classical-nlp-tasks) | NER, QA, Summarization, Translation | 📋 Planned |
| 08 | [🆘 How to Ask for Help](#chapter-08--how-to-ask-for-help) | Debugging, Forums, Community | 📋 Planned |
| 09 | [🌐 Building and Sharing Demos](#chapter-09--building-and-sharing-demos) | Gradio, HuggingFace Spaces | 📋 Planned |
| 10 | [🗂️ Curate High-Quality Datasets](#chapter-10--curate-high-quality-datasets) | Data Collection, Annotation, Quality | 📋 Planned |
| 11 | [⚡ Fine-Tune Large Language Models](#chapter-11--fine-tune-large-language-models) | LoRA, QLoRA, PEFT, RLHF | 📋 Planned |
| 12 | [🧩 Build Reasoning Models](#chapter-12--build-reasoning-models) | Chain-of-Thought, ReAct, Agents | 📋 Planned |

---

## 📖 Chapter Details

### Chapter 01 — Transformer Models

> *Understanding the architecture that changed NLP forever.*

- The self-attention mechanism and why it matters
- Encoder-only (BERT), Decoder-only (GPT), and Encoder-Decoder (T5) architectures
- Transfer learning and why pretrained models are powerful
- Working with `pipeline()` for zero-shot inference

📁 [`Chapter_01_Transformer_Models/`](./Chapter_01_Transformer_Models/)

---

### Chapter 02 — Using Transformers

> *Hands-on with the HuggingFace `transformers` library.*

- The `AutoModel`, `AutoTokenizer`, and `AutoConfig` APIs
- Tokenization deep-dive: input IDs, attention masks, token type IDs
- Model forward pass and understanding logits
- Running multiple NLP tasks with pre-built pipelines

📁 [`Chapter_02_Using_Transformers/`](./Chapter_02_Using_Transformers/)

---

### Chapter 03 — Fine-Tuning a Pretrained Model

> *Adapting pretrained models to custom downstream tasks.*

- Data preprocessing and tokenization for classification
- Using the `Trainer` API for efficient training
- Custom training loops with PyTorch
- Evaluating with `evaluate` and metrics like F1, accuracy

📁 [`Chapter_03_Fine_Tuning_Pretrained_Model/`](./Chapter_03_Fine_Tuning_Pretrained_Model/)

---

### Chapter 04 — Sharing Models and Tokenizers

> *Publishing your work to the HuggingFace Hub.*

- Creating repositories on the HuggingFace Model Hub
- Uploading models and tokenizers with `push_to_hub()`
- Writing professional Model Cards
- Version control for ML models

📁 [`Chapter_04_Sharing_Models_Tokenizers/`](./Chapter_04_Sharing_Models_Tokenizers/)

---

### Chapter 05 — The 🤗 Datasets Library

> *Efficiently handling large-scale NLP datasets.*

- Loading datasets from the Hub and local files
- Dataset operations: map, filter, shuffle, select
- Streaming large datasets without loading to RAM
- Creating and pushing custom datasets to the Hub

📁 [`Chapter_05_Datasets_Library/`](./Chapter_05_Datasets_Library/)

---

### Chapter 06 — The 🤗 Tokenizers Library

> *Building tokenizers from scratch with maximum speed.*

- Byte-Pair Encoding (BPE), WordPiece, Unigram tokenization
- Training a custom tokenizer on your own corpus
- Fast tokenizers and offset mappings
- Integrating custom tokenizers with models

📁 [`Chapter_06_Tokenizers_Library/`](./Chapter_06_Tokenizers_Library/)

---

### Chapter 07 — Classical NLP Tasks

> *End-to-end solutions for core NLP problems.*

- Token classification: Named Entity Recognition (NER)
- Masked Language Modeling (MLM) for pre-training
- Translation and summarization with seq2seq models
- Causal Language Modeling and text generation

📁 [`Chapter_07_Classical_NLP_Tasks/`](./Chapter_07_Classical_NLP_Tasks/)

---

### Chapter 08 — How to Ask for Help

> *Effective debugging and community engagement.*

- Minimal reproducible examples for bug reports
- Using the HuggingFace Forums and GitHub Issues
- Reading error tracebacks and documentation
- Community best practices and contribution guidelines

📁 [`Chapter_08_How_To_Ask_For_Help/`](./Chapter_08_How_To_Ask_For_Help/)

---

### Chapter 09 — Building and Sharing Demos

> *Showcasing ML models with interactive web apps.*

- Building Gradio interfaces for NLP models
- Deploying to HuggingFace Spaces (free hosting)
- Creating blocks-based UI with Gradio Blocks
- Sharing demos and embedding in portfolios

📁 [`Chapter_09_Building_Sharing_Demos/`](./Chapter_09_Building_Sharing_Demos/)

---

### Chapter 10 — Curate High-Quality Datasets

> *The art and science of dataset curation.*

- Web scraping and data collection strategies
- Deduplication, quality filtering, and annotation
- Working with Argilla for human annotation
- Ethical considerations and data governance

📁 [`Chapter_10_Curate_High_Quality_Datasets/`](./Chapter_10_Curate_High_Quality_Datasets/)

---

### Chapter 11 — Fine-Tune Large Language Models

> *Efficiently fine-tuning billion-parameter models.*

- Parameter-Efficient Fine-Tuning (PEFT): LoRA, QLoRA, Adapters
- Reinforcement Learning from Human Feedback (RLHF)
- Direct Preference Optimization (DPO)
- Instruction tuning and chat-model training

📁 [`Chapter_11_Fine_Tune_LLMs/`](./Chapter_11_Fine_Tune_LLMs/)

---

### Chapter 12 — Build Reasoning Models ✨ NEW

> *Building the next generation of intelligent AI systems.*

- Chain-of-Thought (CoT) prompting and reasoning
- ReAct (Reasoning + Acting) agent framework
- Tool use and function calling with LLMs
- Building autonomous AI agents with HuggingFace `smolagents`

📁 [`Chapter_12_Build_Reasoning_Models/`](./Chapter_12_Build_Reasoning_Models/)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python 3.10+ | Core programming language |
| 🤗 `transformers` | Pretrained model loading & fine-tuning |
| 🤗 `datasets` | Efficient dataset handling |
| 🤗 `tokenizers` | Fast, custom tokenization |
| 🤗 `peft` | Parameter-efficient fine-tuning (LoRA, QLoRA) |
| 🔥 PyTorch | Deep learning framework |
| 📓 Jupyter Notebook | Interactive experimentation |
| 📊 Gradio | Model demo interfaces |
| 🌍 HuggingFace Hub | Model & dataset hosting |

---

## 🚀 Getting Started

### Prerequisites

```bash
python >= 3.10
pip or conda for package management
```

### Installation

```bash
# Clone the repository
git clone https://github.com/shivanshu1512/LLM_HuggingFace.git
cd LLM_HuggingFace

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install transformers datasets tokenizers evaluate peft accelerate
pip install torch torchvision torchaudio
pip install gradio jupyter notebook
```

### Running Notebooks

```bash
jupyter notebook
# Navigate to the chapter folder and open any .ipynb file
```

---

## 📈 Learning Progress

```
Chapter  1  ████████████████████  100%  ✅ Transformer Models
Chapter  2  ████████████████████  100%  ✅ Using Transformers
Chapter  3  ████████████░░░░░░░░   60%  🔄 Fine-Tuning
Chapter  4  ██████████░░░░░░░░░░   50%  🔄 Sharing Models
Chapter  5  ██████████░░░░░░░░░░   50%  🔄 Datasets Library
Chapter  6  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Tokenizers Library
Chapter  7  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Classical NLP Tasks
Chapter  8  ░░░░░░░░░░░░░░░░░░░░    0%  📋 How to Ask for Help
Chapter  9  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Building Demos
Chapter 10  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Curate Datasets
Chapter 11  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Fine-Tune LLMs
Chapter 12  ░░░░░░░░░░░░░░░░░░░░    0%  📋 Reasoning Models
```

---

## 🔗 References & Resources

- 📘 [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/) — Official course this repo follows
- 📄 [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — The original Transformer paper
- 📄 [BERT: Pre-training of Deep Bidirectional Transformers](https://arxiv.org/abs/1810.04805)
- 📄 [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- 📄 [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314)
- 🌐 [HuggingFace Hub](https://huggingface.co/) — Models, datasets, and spaces
- 🌐 [smolagents Documentation](https://huggingface.co/docs/smolagents) — Building AI agents

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ If this repository helped you learn, please give it a star! ⭐**

*Made with ❤️ and a lot of ☕ by [Shivanshu Shukla](https://github.com/shivanshu1512)*

</div>
