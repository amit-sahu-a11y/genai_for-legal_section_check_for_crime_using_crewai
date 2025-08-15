# AI Legal Assistant using CrewAI

An **AI-powered legal assistant** built with **CrewAI** that helps lawyers, law firms, and legal professionals automate repetitive tasks such as legal document drafting, case law research, and quick information retrieval.

## Features

- **Legal Document Drafting** – Automatically draft contracts, agreements, and legal notices.  
- **Case Law Research** – Retrieve and summarize case laws quickly using AI-powered search.  
- **Question Answering** – Get instant legal information from large legal datasets.  
- **CrewAI Integration** – Uses CrewAI's multi-agent capabilities for efficient task automation.  
- **Customizable** – Can be adapted for specific jurisdictions or legal domains.  

## Tech Stack

- **Python 3.10+**  
- **CrewAI** for AI agent management  
- **FastAPI / Flask** (if API endpoints are included)  
- **LangChain / LLM Integration** for legal data retrieval  
- **Vector Database (e.g., Chroma / Pinecone)** for document embeddings  
- **Docker** (optional, for deployment)  

## Project Structure

ai-legal-assistant-crewai/
├── agents/ # CrewAI agents and task definitions
├── data/ # Legal datasets or documents
├── models/ # LLM / embeddings configuration
├── app.py # Main entry file (Flask/FastAPI)
├── requirements.txt # Python dependencies
└── README.md # Project documentation
