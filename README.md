## 📚 Virtual Research Assistant — Agentic AI using AutoGen

This project is a Streamlit web application that acts as an intelligent research assistant. It uses a multi-agent system powered by AutoGen to fetch, read, and analyze academic papers from ArXiv in real-time.

Simply enter a research topic, and the agents will find relevant papers, summarize them, and provide a list of their advantages and disadvantages.

## 🚀 Features

* **🖥️ Interactive Web UI**: A clean and simple user interface built with Streamlit.
* **🤖 Multi-Agent Analysis**: Uses two specialized AutoGen agents (a `Summarizer` and an `Analyzer`) to perform complex analysis.
* **⚡ High-Speed Inference**: Powered by the **GROQ API** for extremely fast LLM responses.
* **📄 Automated Data Fetching**: Retrieves the latest research papers directly from the ArXiv API.
* **🗂️ Structured Output**: Presents findings clearly with paper titles, links, summaries, and a pros/cons analysis.

## 🏗️ Tech Stack

* **Python 3.11**
* **Streamlit**: For the interactive web application.
* **AutoGen**: For creating and coordinating the AI agents.
* **GROQ API**: For high-speed LLM reasoning and summarization (openai/gpt-oss-120b).
* **ArXiv API**: For fetching research papers.
* **Scholarly**: For (optional) Google Scholar searches.


## ⚙️ Installation

1️⃣ Clone the repository
```bash
git clone https://github.com/arup04/Autogen_Project
```
Now change the directory
```bash
cd AUTOGEN_PROJECT
```

2️⃣ Create a virtual environment
```bash
uv venv
```

Now activate the virtual environment
#### Linux/Mac:

```Bash
source .venv/bin/activate
```

#### Windows (PowerShell):
```bash
.venv\Scripts\Activate.ps1
```

Windows (Git Bash or CMD):
```Bash
source .venv/Scripts/activate
```

3️⃣ Install dependencies
```bash
uv pip install -r requirements.txt
```

## 🔑 Configuration
This project requires a GROQ API key to function. The application is coded to securely load this key from a .env file.

In the main Autogen_Project folder, create a new file named exactly .env

Open the .env file and add your GROQ API key in the following format:

***GROQ_API_KEY="your_api_key_here"***

Save the file. The .gitignore file in this repository will prevent this file from ever being uploaded to GitHub.

## ▶️ Usage

Once your virtual environment is active and your .env file is configured, you can run the Streamlit application.

In your terminal, run the following command:

```Bash
streamlit run app.py
```
Streamlit will automatically open the application in your default web browser.