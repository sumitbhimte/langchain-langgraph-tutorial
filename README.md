# LangChain, LangGraph, and LangSmith Overview

This repository provides a comprehensive overview and practical examples of using [LangChain](https://github.com/langchain-ai/langchain), [LangGraph](https://github.com/langchain-ai/langgraph), Langsmith and related tools for building advanced LLM-powered applications, including chatbots, agentic workflows, and human-in-the-loop systems.

## Contents

- **LangChain Basics:**  
  Learn how to use LangChain for prompt engineering, sequential chains, and integrating with Google Gemini models.

- **LangChain with Tools:**  
  Demonstrates how to augment LLMs with external tools (e.g., Wikipedia search, custom math functions) and build agentic workflows.

- **LangGraph Linear and Conditional Workflows:**  
  Shows how to use LangGraph to build linear and conditional state graphs for tasks like currency conversion.

- **Chatbot Implementations:**  
  Step-by-step guide to building chatbots using LangChain and LangGraph, including:
  - Simple chatbot with memory
  - Chatbot with tool integration (e.g., stock price lookup, name resolution)
  - Agentic workflows with memory and tool chaining

- **Human-in-the-Loop (HITL):**  
  Example of interrupting agent execution for human approval using LangGraph's `interrupt` and `resume` features.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or VS Code

### Installation

Install all required packages using pip:

```python
pip install google-generativeai langchain langchain-google-vertexai langchain_google_genai langchain-community wikipedia langgraph
```

### Usage

Open [Langchain.ipynb](/Users/sumit/Downloads/Langchain.ipynb) in Jupyter or VS Code and run the cells sequentially.  
The notebook is organized into sections with markdown headers for easy navigation.

- **API Keys:**  
  Make sure to set your Google Gemini API key where required.

- **Custom Tools:**  
  The notebook demonstrates how to define and register your own tools for use with LangChain agents and LangGraph workflows.

- **Visualization:**  
  Graph structures are visualized using Mermaid diagrams within the notebook.

## Features

- **Prompt Engineering:**  
  Use `PromptTemplate` for dynamic prompt creation.

- **Sequential and Conditional Chains:**  
  Combine multiple LLM chains for complex workflows.

- **Tool Integration:**  
  Extend LLM capabilities with custom and built-in tools.

- **Agentic Workflows:**  
  Build agents that can reason, use tools, and remember past interactions.

- **Human-in-the-Loop:**  
  Pause agent execution for human approval on critical actions.

## Example Workflows

- **Restaurant Name and Menu Generator**
- **Math and Wikipedia Agent**
- **Currency Conversion with Conditional Logic**
- **Stock Price Lookup and Name Resolution**
- **Interactive Chatbot with Memory**
- **Approval Workflow for Stock Purchases**

## References

- [LangChain Documentation](https://python.langchain.com/)
- [LangGraph Documentation](https://langgraph.readthedocs.io/)
- [LangSmith](https://smith.langchain.com/)

---

**Note:**  
This notebook is intended as a learning and experimentation resource. For production use, ensure you handle API keys securely and follow best practices for error handling and data privacy.

---

## License

MIT License
