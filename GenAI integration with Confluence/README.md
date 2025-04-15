# 🧠 GenAI Integration with JIRA & Confluence

This project demonstrates the integration of **OpenAI GPT models** with **Atlassian Confluence** using a **Streamlit UI**. It allows users to:

- Query existing Confluence documentation using GPT.
- Generate new documentation with GPT based on user input.
- Automatically publish generated content to Confluence pages.

## 📂 Files

- `genai_confluence_streamlit.ipynb`: Jupyter Notebook containing the full implementation.
- `README.md`: This file.

## 🚀 Features

- 🔐 Fetch Confluence page content via REST API.
- 🤖 Ask GPT-4 questions about Confluence content.
- 📝 Generate requirement documents using OpenAI.
- 📄 Create new Confluence pages automatically with generated content.
- 🎨 Streamlit-based UI for interactive experience.

## ⚙️ Requirements

- Python 3.x
- Streamlit
- OpenAI Python SDK
- `requests` library

Install dependencies:

```bash
pip install streamlit openai requests
```

## 🔑 Environment Variables

**Do NOT hardcode sensitive credentials in the notebook.** Instead, use environment variables:

```bash
export CONFLUENCE_USERNAME="your_email"
export CONFLUENCE_API_TOKEN="your_confluence_token"
export OPENAI_API_KEY="your_openai_api_key"
```

Or manage them securely via a `.env` file with `python-dotenv`.


## 📦 Usage

Run the app locally:

```bash
streamlit run genai_confluence_streamlit.ipynb
```

## 📎 License

This project is intended for internal and educational use only. Not for commercial distribution without consent.