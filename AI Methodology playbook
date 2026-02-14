AI Methodology Playbook
Note: If the cloud deployment link becomes inactive due to expired credits, please refer to the attached project demo video for a complete walkthrough. https://172.26.20.201/ChatBox

The AI Methodology Playbook is a robust, full-stack, multi-turn LLM-powered conversational playbook designed for intelligent interactions. The system leverages adaptive prompt logic, user feedback loops, and real-time WebSocket updates to deliver accurate, responsive, and scalable AI experiences.

The stack is containerized and deployed using Docker, with each service operating as an independent microservice within a shared network and runs the system on Google Cloud Platform (GCP).

Overview
Multi-model, context-aware chatbot with adaptive prompt switching
User feedback loop to improve LLM response accuracy by 35%
Real-time frontend experience with admin monitoring
Modular architecture for scalability and maintainability
Docker-based deployment across all services
Technology Stack
Layer	Tech Stack
Frontend	Next.js, Tailwind CSS
API Server	FastAPI
Data Layer	Flask
LLM Server	FastAPI
Eval Prompt	FastAPI
Database	PostgreSQL
Deployment	Docker, Docker Compose, GCP
Live Updates	WebSocket
Repository Structure
This repository contains Docker configurations to deploy the following components:

Frontend – Next.js interface for user interaction and admin monitoring
API Server – FastAPI application handling routing and orchestration
Data Layer Server – Flask server managing contextual data and metadata
LLM Server – FastAPI server interacting with LLM APIs and logic
Evaluation Prompt Server – FastAPI-based feedback scoring service
PostgreSQL Database – Stores user sessions, prompts, chat history, and feedback
Prerequisites
Docker and Docker Compose installed
PostgreSQL dump files prepared for initialization
Important Notes for Docker Deployment
All services are configured to communicate using Docker container service names rather than localhost. Configuration files and .env settings reflect this change to ensure seamless internal communication.

PostgreSQL is accessible as postgres:5432
Inter-service URLs use container names (e.g., llm-server, api-server)
All containers are connected through the custom Docker network app-network
