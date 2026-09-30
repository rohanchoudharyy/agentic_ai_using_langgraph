# LangGraph Agentic AI Learning

This repository is a hands-on learning journal following a tutorial on agentic AI with LangGraph. It contains small notebooks and Python examples that build up concepts step by step, from basic workflows to tools, persistence, human approval, MCP, and RAG.

## Learning Path

- `0_test_installation.ipynb`: Verify the LangGraph installation.
- `1_bmi_workflow.ipynb`: Build a basic BMI workflow with LangGraph.
- `2_simple_llm_workflow.ipynb`: Create a simple LLM-powered workflow.
- `3_prompt_chaining.ipynb`: Connect prompts into a multi-step workflow.

The notebooks are independent experiments, so you can open any topic directly.

## Setup

Create and activate a virtual environment in PowerShell, then install the project dependencies:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
```

Copy `.env.example` to `.env` and add the API keys needed by the example you want to run. The notebooks load environment variables with `python-dotenv` where applicable. Never commit `.env` or paste API keys into notebooks or source files.

Start Jupyter with:

```powershell
jupyter lab
```

Select the `.venv` Python environment as the notebook kernel.

## Notes

Some examples use external services and require their own API keys or server configuration. The MCP example also contains local and remote server settings that may need to be adapted to your machine.
