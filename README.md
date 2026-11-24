# 🤖 Agentic AI Research Assistant

### An AI-powered multi-agent research system using Groq LLM and Python

## 📌 Project Overview

The **Agentic AI Research Assistant** is an AI-powered application designed to automate research, analysis, and report generation using multiple specialized AI agents.

The application uses Groq LLM to process research topics and coordinate three specialized agents through a Python orchestrator. It also provides an interactive Gradio dashboard.

## ✨ Key Features

- **Research Agent:** Generates background information, trends, developments, opportunities, and challenges.
- **Data Analyst Agent:** Analyzes research and provides key insights, risks, SWOT analysis, and recommendations.
- **Report Agent:** Generates a structured summary report.
- **AI Orchestrator:** Coordinates the agents and manages the research workflow.
- **Function Calling:** Uses a Python calculation tool to calculate percentage growth.
- **Interactive Dashboard:** Displays research, analysis, and final reports using Gradio.

## 🛠️ Technologies Used

- Python
- Groq LLM
- OpenAI-compatible Groq API
- Function Calling
- Multi-Agent AI Architecture
- Gradio
- Google Colab
- FastMCP (installed dependency)

## 🏗️ Project Workflow

1. User enters a research topic.
2. Research Agent generates research content.
3. Data Analyst Agent analyzes the research.
4. Report Agent creates the final report.
5. Python Orchestrator coordinates all three agents.
6. Gradio displays the outputs in separate tabs.

## 📸 Application Interface

The application provides three sections:

- Research
- Analysis
- Final Report

Add your application screenshot to the repository under `screenshots/project-ui.png`.

![Agentic AI Research Assistant](screenshots/project-ui.png)

## 🚀 Installation and Setup

Install the required libraries:

```bash
pip install groq fastmcp gradio requests pydantic
```

## 🔑 API Configuration

This project requires a Groq API key.

1. Get an API key from https://console.groq.com/keys
2. Add it to Google Colab Secrets.
3. Configure the secret name used in your notebook.
4. Never upload your API key to GitHub.

## ▶️ How to Run

1. Open the Google Colab notebook.
2. Configure your Groq API key.
3. Execute the notebook cells in order.
4. Run the final Gradio application cell.
5. Enter a research topic and click **Run Agentic AI Workflow**.

## 📓 Google Colab Notebook

[Open Project in Google Colab](https://colab.research.google.com/drive/16lNacNP79QU0vQc2KvQeSnnUlgF4TkS1?usp=sharing)

## 🎯 Learning Outcomes

- Understanding Agentic AI concepts.
- Building specialized AI agents.
- Integrating Groq LLM with Python.
- Implementing LLM function calling.
- Coordinating multiple agents using an orchestrator.
- Building interactive AI applications with Gradio.

## 👨‍💻 Author

**Srinivas s**

AI & Machine Learning Enthusiast

---

⭐ If you find this project interesting, feel free to explore and star this repository!# Agentic-AI-Research-Assistant
An Agentic AI research assistant powered by Groq LLM, MCP, A2A and Gradio.
