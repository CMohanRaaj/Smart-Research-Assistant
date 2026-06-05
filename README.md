Smart Research Assistant
Overview

Smart Research Assistant is an AI-powered research companion that helps users discover, analyze, and summarize academic research papers using IBM Granite Models, LangFlow, ChromaDB, and Retrieval-Augmented Generation (RAG).

Problem Statement

Researchers often spend significant time searching for relevant literature, reviewing papers, managing references, and extracting insights from multiple sources. Smart Research Assistant automates these tasks and provides intelligent research support.

Features
Academic paper retrieval using arXiv
AI-powered research paper summarization
RAG-based knowledge retrieval
Semantic search using ChromaDB
Research insight generation
Literature review assistance
Context-aware question answering
Agentic AI workflow orchestration
Technology Stack
IBM Granite Models
IBM watsonx.ai
LangFlow
ChromaDB
Retrieval-Augmented Generation (RAG)
Python
IBM Cloud Lite Services
arXiv API
Architecture
User Query
     ↓
Chat Input
     ↓
IBM Granite Model
     ↓
Research Agent
   ↙      ↘
arXiv    ChromaDB
   ↘      ↙
    RAG Retrieval
          ↓
   Research Analysis
          ↓
     Chat Output
Components Used
Chat Input

Accepts research queries from users.

IBM watsonx.ai

Processes queries using IBM Granite Models.

Agent Component

Coordinates tool execution and research workflows.

ChromaDB

Stores vector embeddings and enables semantic retrieval.

arXiv Tool

Retrieves academic papers and publications.

Chat Output

Displays research summaries and insights.

Project Workflow
User submits a research query.
Agent analyzes the query.
arXiv retrieves relevant papers.
ChromaDB performs semantic retrieval.
RAG combines retrieved information.
IBM Granite generates insights.
Results are displayed to the user.
Screenshots

Upload:

LangFlow workflow screenshot
Architecture diagram
Output screenshot

Example:

screenshots/
├── workflow.png
├── architecture.png
└── output.png
Future Scope
IEEE Xplore Integration
Google Scholar Integration
Automated Citation Generation
Research Gap Detection
Research Report Generation
Multi-document Analysis
Project Structure
Smart-Research-Assistant/
│
├── README.md
├── app.json
├── presentation.pptx
├── problem_statement.pdf
├── screenshots/
├── architecture.png
└── requirements.txt
Developer

C. Mohan Raaj
B.E. Computer Science and Engineering
Sathyabama Institute of Science and Technology
