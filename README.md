# Fundamentals-of-AI-Project
Fundamentals of AI Project: AI Research Agent
Developed by: Parth Malguri

Registration Number: 25BCE10325

Project Overview
This project demonstrates the development of an AI Research Agent built upon a foundational Large Language Model (LLM). The agent is designed to go beyond simple chat interactions by autonomously searching for information, synthesizing data, and generating comprehensive research reports.

Unlike a standard LLM, this agent can interact with external tools and follow a multi-step reasoning process to answer complex queries that require up-to-date or specialized knowledge.

Core Concepts
The project explores several key pillars of modern Artificial Intelligence:

Large Language Models (LLMs): Utilizing pre-trained models as the reasoning engine for natural language understanding and generation.

Autonomous Agents: Designing a system that can take a high-level goal (e.g., "Research the impact of quantum computing on RSA encryption") and break it down into actionable steps.

Prompt Engineering: Implementing specific frameworks like ReAct (Reasoning and Acting) to guide the agent through thinking and execution phases.

Tool Use (Function Calling): Enabling the LLM to interact with external APIs, such as web search engines or local file systems, to retrieve real-time data.

Tools and Technologies
The following stack was utilized to build and manage the project:

Programming Language: Python 3.x

AI Frameworks: (e.g., LangChain, OpenAI API, or Hugging Face)

Environment Management: Python venv for isolated dependency management.

Version Control: Git and GitHub for source code management.

Large File Handling: Git LFS (Large File Storage) for managing datasets or model weights.

Repository Structure
.
├── src/                # Core agent logic and scripts
├── data/               # Research datasets (tracked via Git LFS)
├── .gitignore          # Configured to exclude venv and system junk
├── requirements.txt    # List of Python dependencies
└── README.md           # Project documentation


Future Enhancements
Integration of a vector database (like ChromaDB or Pinecone) for RAG (Retrieval-Augmented Generation).

Expansion of toolkits to include academic paper databases (e.g., ArXiv API).

Implementation of a front-end GUI using Streamlit.
