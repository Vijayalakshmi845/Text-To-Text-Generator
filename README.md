# Text-To-Text-Generator
Here's a complete `README.md` file for your **Streamlit + Cohere Text-to-Text Generator** project:

---

````markdown
# 🧠 Text-to-Text Generator using Cohere & Streamlit

This is a simple web application built with **Streamlit** that uses **Cohere's language model** to perform **summarization**, **paraphrasing**, or process a **custom prompt**. Just input your text and choose the task — the app handles the rest using Cohere's `command-xlarge` model.

---

## 📌 Features

- ✅ Summarize any block of text
- ✅ Paraphrase user-entered text
- ✅ Use custom prompts for free-form generation
- ✅ Clean and responsive UI with Streamlit
- ✅ Powered by Cohere's powerful language model

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/cohere-text-generator.git
cd cohere-text-generator
````

### 2. Install Dependencies

Make sure Python is installed, then run:

```bash
pip install streamlit cohere
```

### 3. Add Your API Key

Open the `app.py` (or your filename) and replace:

```python
COHERE_API_KEY = "your_api_key"
```

with your actual [Cohere API key](https://dashboard.cohere.com/api-keys).

Or, use environment variables for better security:

```python
import os
COHERE_API_KEY = os.getenv("COHERE_API_KEY")
```

---

## 💻 Run the App

```bash
streamlit run app.py
```

Then visit the local URL shown in your terminal (usually `http://localhost:8501`).

---

## 📸 UI Preview

> Input your text → Select a task → Get AI-generated output instantly!

---

## 🔒 Security Note

**Do NOT share or commit your Cohere API key.** Use `.env` files or environment variables in production environments.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤖 Powered by

* [Cohere](https://cohere.com)
* [Streamlit](https://streamlit.io)

```

---

Would you like a `.env` setup included as well to keep the API key secure?
```
