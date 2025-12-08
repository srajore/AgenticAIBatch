# AgenticAIBatch

AgenticAIBatch is a small demo repository of Agentic AI examples and exercises built with LangChain and OpenAI. The notebooks show how to create tools, bind them to an LLM, and run agent loops (manual and AgentExecutor approaches).

Contents
- `Agentic_AI_Demo.ipynb` — Introductory walkthrough demonstrating tools, a ReAct loop and a simple agent.
- `Day2_DeepDive.ipynb` — Day 2 deep dive: tools, StructuredTool (Pydantic), manual execution loop.
- `Day2_Capstone_AgentExecutor.ipynb` — Project Nexus: an AgentExecutor-based implementation of a client assistant.
- `requirements.txt` — Python dependencies for running the notebooks.

Recent commits (most recent first):
- deb6806  Auto-sync: commit from assistant (payalsr, 2025-12-08)
- e6cf4ef  Update requirements.txt and add new langgraph demo notebooks (payalsr, 2025-12-05)
- 7709a67  introduction to langgraph (payalsr, 2025-12-02)
- 812bdbe  Capstone project Project Nexus (payalsr, 2025-11-28)
- 4497216  custom and built-in tools (payalsr, 2025-11-27)

Quick start
1. Create & activate a virtual environment (Windows cmd):

```cmd
D:\> python -m venv venv
D:\> venv\Scripts\activate
```

2. Install dependencies:

```cmd
(venv) D:\AgenticAI> python -m pip install -r requirements.txt
```

3. Open the notebooks with Jupyter or VS Code and run cells in order. Provide your `OPENAI_API_KEY` when prompted.

Notes
- Do not commit secrets. The repo `.gitignore` excludes `venv/` and `.env` by default.
- If your corporate network blocks web scraping search tools, use the included mock tools or configure an API-based search provider (Tavily).

License
- MIT
