# FinRL-DeepSeek: Automated Stock Trading with LLM and RL

## AI for Finance - Term Project

This repository contains the methodology and conceptual framework for integrating DeepSeek Large Language Models (LLMs) with Reinforcement Learning (RL) for stock trading, developed for the **FinRL Contest 2025 (Task I)**.

### Overview
Traditional Reinforcement Learning agents rely solely on historical numerical data. This project uses the **FinRL-DeepSeek** approach to inject real-time market sentiment and risk assessment directly into the trading agent.

### Dataset
We utilize the **FNSPID** (Financial News and Stock Price Integration Dataset), which aligns stock prices with 15 million financial news articles from 1999-2023.

### Architecture
1. **LLM Signal Extractor (DeepSeek):** Processes daily financial news to generate a sentiment score (-1 to 1) and a risk indicator.
2. **RL Agent (PPO/GRPO):** Takes a combined state space `[OHLCV + Technical Indicators + LLM Sentiment + LLM Risk]` to output continuous trading actions (portfolio weights).

### Repository Structure
- `Term_Paper_FinRL_DeepSeek.pdf` : The research paper submitted for the course.
- `/docs` : Methodology and prompt engineering details.

*(Note: Full source code is under active development for the contest submission).*
