# OpenAI API Cookbook

Production-ready patterns for OpenAI APIs with working Python code examples.

## Notebooks

### 1. Code Generation Agent

Automatically generate, test, and execute Python code from natural language queries.

**Features:**
- Function generation from plain English descriptions
- Automatic test case creation and validation
- Retry mechanism for improved reliability
- Self-correcting code execution

**Example:**
```
Query: "Write a function to find the nth Fibonacci number"
→ Generates function + test cases + executes validation
```

### 2. Multi-Agent Data Analysis

Coordinated AI agents for comprehensive data analysis workflows on real datasets.

**Agent Architecture:**
```
User Query → Planning Agent → Python Agent → Summarization Agent → Final Report
```

| Agent | Role |
|-------|------|
| **Planning Agent** | Creates comprehensive analysis strategy |
| **Python Agent** | Generates and executes analytical code |
| **Summarization Agent** | Produces final insights report |

**Demo Dataset:** World Happiness Report - statistical analysis and insights

### 3. Conversation Simulator

Simulate engaging dialogues between personas with context retention across turns.

**Features:**
- Persona-specific speaking styles and viewpoints
- Multi-turn context maintenance
- Dynamic topic exploration
- Entertaining and educational simulations

## Quick Start

```bash
# Install dependencies
pip install openai pandas jupyter

# Set your API key
export OPENAI_API_KEY=your_key_here

# Launch notebooks
jupyter notebook
```

## Requirements

- Python 3.8+
- OpenAI API key
- pandas (for data analysis notebook)
- Jupyter Notebook

## Tech Stack

- **LLM**: GPT-4 / GPT-4-Turbo
- **API**: OpenAI Python SDK
- **Data**: pandas, numpy
- **Environment**: Jupyter Notebooks

## License

MIT
