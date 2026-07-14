🔬 ResearchMind – Multi-Agent AI Research System

**An AI-powered Multi-Agent Research Assistant that autonomously searches the web, extracts information from trusted sources, generates comprehensive research reports, and critiques its own output using specialized AI agents.**


📖 Overview

ResearchMind is an **Agentic AI-based Multi-Agent Research System** built with **LangChain**, **Mistral AI**, **Tavily Search API**, and **Streamlit**.

Unlike conventional AI assistants that rely on a single LLM response, ResearchMind divides the research process into multiple specialized AI agents. Each agent performs a dedicated task—searching, reading, writing, and reviewing—to generate accurate, comprehensive, and high-quality research reports.

The modular architecture improves reliability, scalability, and research quality while demonstrating real-world applications of Agentic AI.


✨ Features

- 🔍 AI-powered Web Search
- 🤖 Multi-Agent Architecture
- 📄 Intelligent Web Scraping
- ✍️ Automated Research Report Generation
- 🧐 AI-based Report Evaluation
- ⚡ Beautiful Streamlit User Interface
- 📥 Download Research Reports
- 🧩 Modular & Scalable Design


## 🏗️ Architecture


                    User Query
                         │
                         ▼
                🔍 Search Agent
          (Find Reliable Sources)
                         │
                         ▼
                📄 Reader Agent
       (Scrape & Extract Information)
                         │
                         ▼
                ✍️ Writer Chain
      (Generate Research Report)
                         │
                         ▼
                🧐 Critic Chain
      (Evaluate & Score Report)
                         │
                         ▼
              Final Research Output

## 🔄 Workflow

### 🔍 Search Agent

- Searches the web using Tavily Search API
- Retrieves recent and reliable information
- Returns relevant URLs and summaries

### 📄 Reader Agent

- Selects the most relevant source
- Scrapes webpage content
- Cleans and extracts meaningful text

### ✍️ Writer Chain

Creates a structured research report including:

- Introduction
- Key Findings
- Conclusion
- References

### 🧐 Critic Chain

Reviews the generated report by providing:

- Overall Score
- Strengths
- Areas of Improvement
- Final Verdict

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Framework | LangChain |
| Large Language Model | Mistral AI |
| Search API | Tavily Search |
| Web Scraping | BeautifulSoup, Requests |
| Frontend | Streamlit |
| Environment | Python-dotenv |

---

## 📂 Project Structure

```text
ResearchMind/
│
├── agents.py
├── pipeline.py
├── tools.py
├── ui.py
│
├── requirements.txt
├── .env.example
├── README.md
└── .gitignore
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/ResearchMind.git

cd ResearchMind
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / macOS**

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create a `.env` File

```env
MISTRAL_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key
```

### Run the Application

```bash
streamlit run ui.py
```

---

## 💻 Example

### Input

```
Latest advancements in Quantum Computing
```

### Output

- Web Search Results
- Extracted Web Content
- Structured Research Report
- AI-generated Evaluation & Score

---

## 🎯 Use Cases

- Academic Research
- Literature Reviews
- Business Intelligence
- Market Analysis
- Technology Research
- Competitive Analysis
- Student Projects
- AI-assisted Documentation

---

## 🚀 Future Enhancements

- PDF Export
- Citation Generator
- Parallel Agent Execution
- Multi-LLM Support
- RAG Integration
- Research History
- Source Credibility Ranking
- Memory-enabled Agents
