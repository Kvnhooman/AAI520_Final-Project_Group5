# AAI520_Final-Project_Group5

Kevin Hooman, Spencer Cody, Tommy Poole

## Overview
This project implements a modular AI assistant that leverages large language models (LLMs), retrieval-augmented generation (RAG), and agentic workflows to automate financial research and analysis. The system is designed to:

Aggregate and summarize financial data from multiple sources (Yahoo Finance, SEC EDGAR, etc.)

Analyze SEC filings and extract key insights

Evaluate investment opportunities using dynamic feedback loops

Incorporate human feedback for iterative improvement

## Features
* Multi-Agent Orchestration: Specialized agents for research, evaluation, and optimization.

* Financial Data Aggregation: Automated retrieval of stock prices, ratios, and company fundamentals.

* SEC Filings Analysis: Extraction and summarization of 8-K, 10-K, and other filings.

* Sentiment Analysis: Uses Hugging Face models for financial news and filings.

* Human-in-the-Loop Feedback: Interactive workflow for refining analysis and recommendations.

* Markdown Reporting: Outputs formatted investment summaries and commentary.

## Example Workflow
Research Agent: Aggregates financial data and filings for a given stock symbol.

Evaluator Agent: Reviews the summary, checks for completeness, and incorporates human feedback.

Optimization Loop: Iteratively refines the analysis based on feedback and additional data sources.

## Key Technologies
1. Python 3.x
2. LangChain & LangGraph (agent orchestration)
3. Hugging Face Transformers (LLMs, sentiment analysis)
4. SEC EDGAR API
5. Yahoo Finance API

