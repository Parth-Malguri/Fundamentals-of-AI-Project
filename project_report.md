Project Report: Autonomous AI Research Agent
Student Name: Parth Malguri

Registration Number: 25BCE10325

Course: Fundamentals of AI

Project Title: Development of a Simple LLM-Based Research Agent

1. Introduction
The objective of this project is to bridge the gap between static Large Language Models (LLMs) and autonomous agents. While standard LLMs are limited to the knowledge present in their training data, a Research Agent is designed to use tools and reasoning loops to fetch, verify, and synthesize information from external sources. This project focuses on implementing a "Reasoning and Acting" (ReAct) cycle to perform autonomous research tasks.

2. Objectives
To implement a functional AI agent capable of breaking down complex research queries.

To integrate external tool-use capabilities (e.g., Web Search, File I/O) into an LLM framework.

To manage large-scale data and model dependencies using version control systems like Git LFS.

To ensure reproducible results through isolated virtual environments.

3. Core AI Concepts Applied
3.1 Large Language Models (LLMs)
The core "brain" of the agent is a transformer-based LLM. It is responsible for parsing user intent and generating human-like summaries based on retrieved data.

3.2 Agentic Workflow (ReAct Logic)
The agent follows a structured thought process:

Thought: The agent analyzes the user prompt and determines what information is missing.

Action: The agent selects a specific tool (e.g., a search engine) to find that information.

Observation: The agent reads the results provided by the tool.

Repeat: This cycle continues until the agent has enough information to form a final answer.

3.3 Prompt Engineering
System prompting is used to define the agent's persona, constraints, and output format. This ensures the agent remains focused on research and cites its sources accurately.

4. System Design and Tools
4.1 Technical Stack
Python 3.x: The primary programming language for logic and API integration.

OpenAI/Hugging Face APIs: Used to access the underlying LLM weights.

LangChain / Custom Agent Logic: Used to orchestrate the flow between the model and the tools.

4.2 Version Control and Data Management
Git & GitHub: Used for source code versioning and collaborative tracking.

Git LFS (Large File Storage): Implemented to handle large datasets or binary model files that exceed GitHub’s standard 100 MB limit.

.gitignore Configuration: Optimized to exclude local virtual environments (venv/) while ensuring project-critical code and LFS pointers are tracked.

5. Implementation Process
Environment Setup: Created a virtual environment to manage dependencies and avoid library conflicts.

Model Integration: Connected the script to an LLM provider via API.

Tool Definition: Created Python functions that allow the agent to perform Google searches and read local text files.

Agent Loop: Developed the main execution loop where the agent iterates through "Thought" and "Action" phases.

Testing: Verified the agent’s ability to answer real-time questions (e.g., "What are the latest developments in Fusion Energy as of 2026?").

6. Results and Discussion
The agent successfully demonstrated the ability to perform multi-step research. By utilizing external tools, it overcame the "knowledge cutoff" limitation typical of standard LLMs. The integration of Git LFS ensured that the repository remained lightweight while still providing access to the necessary large-scale data components required for AI research.

7. Conclusion
This project highlights the potential of autonomous agents in streamlining academic and professional research. Future iterations will focus on improving the agent's memory (allowing it to remember previous research sessions) and integrating vector databases for faster information retrieval.