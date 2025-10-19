🧠 Financial Research AI Assistant

Authors: Tommy Poole, Spencer Cody, Kevin Hooman
Instructor: Dr. Andrew Van Benschoten
Date: Fall 2025

⸻

📘 Overview

The Financial Research AI Assistant is a modular, multi-agent system that automates financial research, data aggregation, and analysis using LLM-powered reasoning and retrieval augmented generation (RAG).

Developed for the AAI 520: NLP and GenAI course, this project showcases a real world implementation of agent orchestration, reflection, and workflow automation in financial analysis. From retrieving stock data and SEC filings to summarizing findings and generating insights.

⸻

⚙️ Core Features

🧩 Multi-Agent Architecture

The system uses four specialized agents that communicate in a dynamic workflow:
	•	Planner Agent: Designs a step-by-step research plan and assigns tasks.
	•	Research Agent: Gathers and preprocesses financial data via APIs and datasets.
	•	Evaluator Agent: Analyzes and verifies retrieved data and summaries for quality.
	•	Optimizer Agent: Applies self-reflection to refine and improve outputs.

🔄 Workflow Patterns Implemented
	1.	Prompt Chaining: Sequential reasoning steps (ingest → classify → summarize).
	2.	Routing to Specialists: Directs tasks to domain-specific agents.
	3.	Evaluator–Optimizer Loop: Iterative process of generation, evaluation, and refinement.
	4.	Memory Pattern: Agents log reflections to enhance reasoning in future runs.

⸻

🧱 Project Structure

📂 Financial_Research_AI_Assistant/

│

├── Fina_Resear_Financial_AI_Assistant.ipynb

├── data/
├── outputs/
├── requirements.txt
└── README.md


⸻

🧰 Tools & Libraries

Category	Libraries / Tools
Core	Python 3.10+, Jupyter Notebook
Data Retrieval	yfinance, requests, alpha_vantage
Data Processing	pandas, numpy
LLM & Agentic Frameworks	openai, transformers, langchain, langgraph
Visualization	matplotlib, seaborn


⸻

🚀 How to Run
	1.	Install dependencies:

pip install -r requirements.txt


	2.	Launch the notebook:

jupyter notebook Fina_Resear_Financial_AI_Assistant.ipynb


	3.	Set parameters (e.g., stock symbol):

symbol = "AAPL"  # or any desired ticker


	4.	Run all cells sequentially.
The assistant will:
	•	Plan a workflow
	•	Retrieve stock and filing data
	•	Summarize findings
	•	Evaluate and refine results

⸻

📊 Example Outputs

💼 Company Analysis

Summaries include:
	•	Key financial ratios and trends
	•	Market and stock price data
	•	Risk factors extracted from SEC filings

🧠 Reflection Logs

Each agent records its reasoning process and self-assessment for iterative improvement.

📈 Visual Outputs

The notebook produces plots of financial indicators and sentiment summaries.

⸻

🎯 Learning Outcomes
	•	Built a multi-agent workflow with LLM-based reasoning.
	•	Integrated RAG pipelines for factual financial data retrieval.
	•	Implemented reflection and evaluation loops for quality assurance.
	•	Demonstrated end-to-end automation in a realistic AI system design context.

⸻

🔮 Future Improvements
	•	Integrate NewsAPI for real-time financial sentiment analysis.
	•	Add vector database memory (FAISS/Chroma) for long-term knowledge.
	•	Create an interactive web interface using Streamlit or Replit.
	•	Expand evaluator logic for more robust financial comparisons.

⸻

📚 References
	•	Yahoo Finance API
	•	SEC EDGAR Database
	•	LangChain Documentation
	•	LangGraph Framework
	•	University of San Diego – AAI 520 Course Materials

⸻
