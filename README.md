# AI Research Agent

An AI-powered Research Agent built using **LangChain**, **Groq LLM**, and **Python**. The agent leverages external tools to gather information, reason over queries, and provide intelligent responses.

## Features

- AI-powered research assistant
- LangChain agent architecture
- Groq LLM integration
- Tool-based reasoning
- Wikipedia search
- ArXiv paper search
- Environment variable support with `.env`

## Tech Stack

- Python
- LangChain
- Groq
- LangSmith
- ArXiv API
- Wikipedia API
- Python Dotenv

## Project Structure

```
ai-research-agent/
│
├── agents/
│   └── agents.ipynb
│
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/ai-research-agent.git
cd ai-research-agent
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root.

```env
LANGCHAIN_API_KEY=your_langchain_api_key
GROQ_API_KEY=your_groq_api_key
LANGCHAIN_PROJECT=AI-Research-Agent
LANGCHAIN_TRACING=true
```

## Running the Project

Open the Jupyter Notebook:

```
agents/agents.ipynb
```

Run all cells to interact with the AI Research Agent.

## Future Improvements

- Web search integration
- Multi-agent workflows
- Memory support
- Streamlit interface
- FastAPI deployment

## Author

Mohd Faizaan

---

If you found this project useful, consider giving it a ⭐ on GitHub.
