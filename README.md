# 🧠 AI Text Humanizer

Welcome to **AI Text Humanizer** — an open-source project featuring two intelligent text rewriters that turn mechanical or AI-generated writing into fluent, natural-sounding language.

## 💡 Overview

This project includes **two unique Python-based humanizers**:

| Humanizer | Description |
|------------|--------------|
| 🟢 **Balanced** | Focuses on clarity, grammar, and readability while keeping the tone similar to the input. |
| 🔴 **Aggressive** | Performs stronger rephrasing and stylistic variation, perfect for making text sound creatively human. |

Both versions leverage modern NLP tools such as **Transformers**, **spaCy**, **TextStat**, and **NLTK** for grammatical and stylistic refinement.

## ✨ Features

### 🌐 Web UI
- **Easy-to-use interface** with Streamlit
- **Two humanizer modes**: Balanced and Aggressive
- **Multiple input methods**: Paste text, upload files, or use samples
- **Real-time statistics**: See AI detection scores and improvement metrics
- **Download & copy**: Save your humanized text easily
- **Responsive design**: Works on desktop and mobile

### 📓 Jupyter Notebooks
- **Detailed implementation** of both humanizers
- **Customizable parameters** for advanced users
- **Step-by-step explanations** of the humanization process

---

## 🚀 Getting Started

### Web UI (Recommended)

The easiest way to use the AI Text Humanizer is through our **Streamlit web interface**:

```bash
cd web_ui
pip install -r requirements.txt
python -m spacy download en_core_web_sm
streamlit run app.py
```

See the [Web UI Quick Start Guide](web_ui/QUICKSTART.md) for detailed instructions.

### Jupyter Notebooks

For advanced users who want to work with the code directly:

```bash
git clone https://github.com/AnikethBhosale/ai-humanizers.git
cd ai-humanizers
pip install -r requirements.txt
```

Then open `humanizer_balanced.ipynb` or `humanizer_aggressive.ipynb` in Jupyter.

## Tech Stack
- Python 🐍

- Transformers 🤗

- spaCy

- NLTK

- TextStat

- Scikit-Learn

- Pandas / NumPy

##  🧑‍💻 Contributing

We welcome all kinds of contributions, especially during Hacktoberfest 2025 🎉

How to Contribute

Fork the repo

Create your branch: git checkout -b feature-name

Commit your changes: git commit -m "Add <feature>"

Push to your fork and open a Pull Request

Please open an issue first if you’re working on a new feature.

## 🏷️ Hacktoberfest Participation

This repository is participating in Hacktoberfest 2025.
Look for issues labelled:

hacktoberfest

good first issue

python

## 🪪 License

This project is licensed under the MIT License

## 🌟 Acknowledgements

The open-source NLP community (spaCy, Hugging Face, TextStat)

All contributors making AI text more human ❤️


