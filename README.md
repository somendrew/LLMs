# 🤖 LLMs — Large Language Model Experiments & Learning

A hands-on collection of notebooks exploring the internals, capabilities, and practical applications of Large Language Models (LLMs). From understanding transformer architecture to building RAG pipelines and AI agents — this repo documents the full learning journey.

-----

## 📚 What’s Inside

|Notebook                                        |Description                                                                                                                  |
|------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
|`LLM_01_How_to_use_LLMs_with_hugging_face.ipynb`|Getting started with Hugging Face `transformers` — loading models, tokenization, inference                                   |
|`LLM1_HuggingFace.ipynb`                        |Deeper dive into Hugging Face pipelines and model hub usage                                                                  |
|`Self_Multihead_positional_notes.ipynb`         |Understanding self-attention, multi-head attention, and positional encoding from scratch                                     |
|`RAG_From_Scratch.ipynb`                        |Building a Retrieval-Augmented Generation (RAG) pipeline from first principles — embeddings, vector search, context injection|
|`RAG_using_LangChain.ipynb`                     |Implementing RAG with LangChain — document loaders, vector stores, and conversational chains                                 |
|`Tool_Calling_tutorial.ipynb`                   |How LLMs use tools/function calling — practical examples with structured outputs                                             |
|`Building_an_AI_Agent_using_OpenAI_API.ipynb`   |End-to-end AI agent with memory, tool use, and reasoning loops using the OpenAI API                                          |

-----

## 🛠️ Tech Stack

|Tool                     |Purpose                            |
|-------------------------|-----------------------------------|
|Python                   |Core language                      |
|Hugging Face Transformers|Model loading & inference          |
|LangChain                |RAG pipelines & agent orchestration|
|OpenAI API               |GPT-based agent and tool calling   |
|FAISS / Vector Stores    |Semantic search for RAG            |
|Jupyter Notebook         |Interactive development            |

-----

## 🧠 Concepts Covered

- **Transformer Architecture** — Self-attention, multi-head attention, positional encoding
- **Hugging Face Ecosystem** — Pipelines, tokenizers, model hub
- **RAG (Retrieval-Augmented Generation)** — From scratch and with LangChain
- **Tool / Function Calling** — Structured LLM outputs
- **AI Agents** — Memory, planning, and tool use loops

-----

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/somendrew/LLMs.git
cd LLMs

# Install dependencies
pip install transformers langchain openai faiss-cpu sentence-transformers torch

# Open any notebook
jupyter notebook RAG_From_Scratch.ipynb
```

> **Note:** For OpenAI API notebooks, you’ll need an API key set as an environment variable:
> 
> ```bash
> export OPENAI_API_KEY="your-key-here"
> ```

-----

## 📌 Highlights

- Built RAG from scratch — no LangChain abstraction — to deeply understand vector search and context injection
- Implemented a full AI agent with tool calling and memory management
- Covered transformer internals including self-attention math and positional encodings

-----

## 🔗 Related Projects

- [GenZify-1.5B](https://github.com/somendrew/GenZify-1.5B) — Fine-tuned Qwen2.5 using QLoRA + PEFT

-----

## 👤 Author

**Somendra Singh**

- 🔗 [LinkedIn](https://linkedin.com/in/somendrew)
- 🐙 [GitHub](https://github.com/somendrew)
- 📊 [Kaggle](https://kaggle.com/somendrew)
