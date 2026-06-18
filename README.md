<div align="center">

# 🤗 LLM & HuggingFace — Complete Learning Journey

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow?logo=huggingface&logoColor=white)](https://huggingface.co/transformers/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Chapters](https://img.shields.io/badge/Chapters-12-purple)](.)
[![Course](https://img.shields.io/badge/Based%20On-HuggingFace%20NLP%20Course-orange)](https://huggingface.co/learn/nlp-course/)

**Structured notes, certificates, and key learnings from the [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/) — covering transformer architectures through building autonomous reasoning agents.**

</div>

---

## 📚 Chapters

| # | Chapter | Topics | Status |
|---|---------|--------|--------|
| 01 | [Transformer Models](./Chapter_01_Transformer_Models/) | Architecture, Self-Attention, BERT, GPT | ✅ Done |
| 02 | [Using Transformers](./Chapter_02_Using_Transformers/) | Pipelines, AutoModel, AutoTokenizer | ✅ Done |
| 03 | [Fine-Tuning a Pretrained Model](./Chapter_03_Fine_Tuning_Pretrained_Model/) | Trainer API, Training Loop, Metrics | ✅ Done |
| 04 | [Sharing Models and Tokenizers](./Chapter_04_Sharing_Models_Tokenizers/) | HuggingFace Hub, Model Cards | ✅ Done |
| 05 | [The Datasets Library](./Chapter_05_Datasets_Library/) | Loading, Processing, Streaming | ✅ Done |
| 06 | [The Tokenizers Library](./Chapter_06_Tokenizers_Library/) | BPE, WordPiece, Fast Tokenizers | ✅ Done |
| 07 | [Classical NLP Tasks](./Chapter_07_Classical_NLP_Tasks/) | NER, Summarization, Translation, QA | ✅ Done |
| 08 | [How to Ask for Help](./Chapter_08_How_To_Ask_For_Help/) | Debugging, Community, Forums | ✅ Done |
| 09 | [Building and Sharing Demos](./Chapter_09_Building_Sharing_Demos/) | Gradio, HuggingFace Spaces | ✅ Done |
| 10 | [Curate High-Quality Datasets](./Chapter_10_Curate_High_Quality_Datasets/) | Collection, Annotation, Filtering | ✅ Done |
| 11 | [Fine-Tune Large Language Models](./Chapter_11_Fine_Tune_LLMs/) | LoRA, QLoRA, PEFT, RLHF, DPO | ✅ Done |
| 12 | [Build Reasoning Models](./Chapter_12_Build_Reasoning_Models/) | Chain-of-Thought, ReAct, Agents | ✅ Done |

---

## 📖 Chapter Summaries

### 01 — Transformer Models
Self-attention mechanism, encoder/decoder/encoder-decoder architectures (BERT, GPT, T5), and transfer learning fundamentals.

### 02 — Using Transformers
`AutoModel`, `AutoTokenizer`, `AutoConfig` APIs; tokenization internals — input IDs, attention masks, token type IDs.

### 03 — Fine-Tuning a Pretrained Model
Data preprocessing, `Trainer` API, custom PyTorch training loops, evaluation with F1 and accuracy metrics.

### 04 — Sharing Models and Tokenizers
Publishing to HuggingFace Hub with `push_to_hub()`, writing Model Cards, version control for ML artifacts.

### 05 — The Datasets Library
Loading from Hub and local files, map/filter/shuffle/select operations, streaming large corpora, creating custom datasets.

### 06 — The Tokenizers Library
BPE, WordPiece, and Unigram algorithms; training tokenizers from scratch; fast tokenizers and offset mappings.

### 07 — Classical NLP Tasks
Token classification (NER), masked LM pre-training, seq2seq translation and summarization, causal LM text generation.

### 08 — How to Ask for Help
Debugging strategies, minimal reproducible examples, navigating HuggingFace Forums and GitHub Issues effectively.

### 09 — Building and Sharing Demos
Gradio interfaces, Gradio Blocks, deploying to HuggingFace Spaces, embedding demos in portfolios.

### 10 — Curate High-Quality Datasets
Data collection pipelines, deduplication, quality filtering, human annotation with Argilla, dataset ethics.

### 11 — Fine-Tune Large Language Models
LoRA and QLoRA via PEFT library, instruction tuning, RLHF, Direct Preference Optimization (DPO).

### 12 — Build Reasoning Models
Chain-of-Thought prompting, ReAct (Reasoning + Acting) framework, tool use / function calling, autonomous agents with `smolagents`.

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| 🤗 `transformers` | Model loading, inference & fine-tuning |
| 🤗 `datasets` | Dataset loading and processing |
| 🤗 `tokenizers` | Fast, customizable tokenization |
| 🤗 `peft` | LoRA, QLoRA, adapter-based fine-tuning |
| 🔥 PyTorch | Deep learning backend |
| 📊 Gradio | Interactive model demos |
| 🌍 HuggingFace Hub | Model & dataset hosting |

---

## 🔗 Key References

- [HuggingFace NLP Course](https://huggingface.co/learn/nlp-course/)
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [BERT Paper](https://arxiv.org/abs/1810.04805)
- [LoRA Paper](https://arxiv.org/abs/2106.09685)
- [QLoRA Paper](https://arxiv.org/abs/2305.14314)
- [smolagents Docs](https://huggingface.co/docs/smolagents)

---

<div align="center">
<sub>MIT License · <a href="https://github.com/shivanshu1512">Shivanshu Shukla</a></sub>
</div>
