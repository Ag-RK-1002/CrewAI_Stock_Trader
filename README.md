# 🤖📈 CrewAI Stock Trader Agents

A multi-agent AI system built using [CrewAI](https://github.com/joaomdmoura/crewai) and [LangChain](https://github.com/hwchase17/langchain) to research, analyze, and recommend the best stocks for investment based on real-time data and risk-reward profiles.

---

## 🚀 Project Overview

This project simulates a virtual investment assistant powered by Large Language Models (LLMs) that:

- 💡 Researches market trends and stock data
- 📊 Analyzes risk vs. reward for different stocks
- ✅ Recommends the most promising investment option

It does this by using a team of autonomous AI agents—each with a distinct role—working together to evaluate financial data and suggest the best stock to buy.

---

## 🧠 Core Agents

| Agent | Role |
|-------|------|
| 🕵️ Researcher | Uses a web search tool to gather recent stock data for a sector |
| 📈 Analyst | Evaluates stocks based on their risk and reward profiles |
| 🧑‍⚖️ Executor | Decides and outputs the best stock to invest in |

---

## 🧰 Tech Stack

- **Python**
- **CrewAI** – agent-based orchestration
- **LangChain** – for chaining LLM workflows
- **DuckDuckGoSearch** – real-time stock search tool
- **OpenAI API** – powering the agents' intelligence

---

## 🗂️ Project Structure

```bash
CrewAI_Stock_Trader/
│
├── agents.py               # Defines AI agents and their roles
├── crewai_stock_trader.py  # Orchestrates the agents into a crew
├── tools.py                # Custom tool: DuckDuckGo stock search
├── .env                    # OpenAI API keys and model config
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
