# 🤖 Building with Claude API

> A hands-on collection of Jupyter notebooks exploring the Claude API — from first requests to advanced patterns.

---

## 📚 About This Repo

This repository is a practical learning journey through the **Anthropic Claude API**. Each notebook focuses on a specific concept, building progressively from the basics to more powerful features.

Whether you're just starting out or looking to deepen your understanding, you'll find clean, well-commented examples that you can run and experiment with.

---

## 🗂️ Notebooks

| # | Notebook | Description |
|---|----------|-------------|
| 001 | `001_request.ipynb` | First API request — setting up the client, authentication, and making a basic call to Claude |

> More notebooks coming soon! ⚡

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- An [Anthropic API key](https://console.anthropic.com/)
- Jupyter Notebook or JupyterLab

### Installation

```bash
# Clone the repo
git clone https://github.com/SergioLucasLopez/building-with-claude-api.git
cd building-with-claude-api

# Install dependencies
pip install anthropic python-dotenv jupyter
```

### Configuration

Create a `.env` file in the root of the project:

```env
ANTHROPIC_API_KEY=your_api_key_here
```

> ⚠️ Never commit your `.env` file. Add it to `.gitignore`.

### Run a Notebook

```bash
jupyter notebook
```

Then open any `.ipynb` file and run the cells in order.

---

## 🧩 What You'll Learn

- ✅ How to authenticate and initialize the Anthropic client
- ✅ How to send messages and receive responses
- ✅ How to inspect response objects and extract content
- 🔜 Working with system prompts
- 🔜 Multi-turn conversations
- 🔜 Streaming responses
- 🔜 Tool use & function calling
- 🔜 Vision & document analysis

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude_API-orange?logo=anthropic)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  Made with ❤️ and a lot of Claude
</div>
