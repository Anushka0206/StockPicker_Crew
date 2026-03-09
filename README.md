# StockPicker Crew 📈

An AI-powered multi-agent system built with [crewAI](https://crewai.com) to automate stock market research and analysis. This project leverages collaborative AI agents to evaluate technology sector leaders and provide actionable investment insights.

## 🌟 Overview
The StockPicker Crew consists of specialized AI agents that work together to:
1.  **Analyze Market Trends**: Research the latest developments in specific sectors (e.g., AI, Cloud, AR).
2.  **Evaluate Financials**: Review earnings reports and performance metrics.
3.  **Generate Reports**: Compile data into a structured `report.md` for investment decision-making.

## 🛠 Installation

Ensure you have Python `3.10 <= version < 3.13` installed. This project uses [UV](https://docs.astral.sh/uv/) for fast dependency management.

1. **Install UV** (if not already installed):
   ```bash
   pip install uv

2. **Install Dependencies**
   ```bash
   crewai install

3. **Run the crew**
      ```bash
      crewai run

## 📂 Project Structure
1.src/stock_picker/config/agents.yaml: Define agent roles and goals.
2.src/stock_picker/config/tasks.yaml: Define the workflow and task descriptions.
3.src/stock_picker/crew.py: Core logic and agent orchestration.
4.src/stock_picker/main.py: Entry point for passing custom inputs.
