# AgentCore Short-Term Memory — Learning Project

This repository contains a **learning-focused example** demonstrating **short-term memory (STM)** and **checkpointing** in agents built with **Amazon Bedrock AgentCore**.

The project is based on a tutorial-style workflow and focuses on understanding how agent state is managed, persisted, and resumed during execution.

---

## 📦 What This Project Contains

* A notebook-based example of an **AgentCore-powered agent**
* Usage of **short-term memory** for maintaining conversational and reasoning state
* **Checkpointing** of agent execution state using AWS-backed storage
* Graph-based control flow for agent reasoning steps

---

## 🧰 Technologies Used

### Agent & Memory

* **Amazon Bedrock AgentCore** (`bedrock_agentcore`) — agent runtime and short-term memory
* **LangGraph** (`langgraph`) — graph-based agent orchestration
* **LangGraph Checkpoint AWS** (`langgraph-checkpoint-aws`) — checkpoint persistence on AWS

### LLM & AWS Integration

* **Boto3** (`boto3`) — AWS SDK for Bedrock access
* **LangChain AWS** (`langchain_aws`) — AWS-compatible LLM integrations
* **LangChain Core** (`langchain_core`) — core abstractions for prompts and messages

### Development

* **Jupyter Notebook / IPython** — interactive experimentation and inspection

---

## 📁 Repository Structure

```
.
├── math-agent-with-checkpointing.ipynb
├── requirements.txt
└── README.md
```

---

## 📄 Notes

* This is **not a production-ready system**.
* Dependencies are intentionally minimal and scoped to this example.
