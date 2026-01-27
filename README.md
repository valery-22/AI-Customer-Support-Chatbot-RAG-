# AI-Customer-Support-Chatbot-RAG-
Overview
- RAG system using FastAPI, FAISS, and LLM APIs to answer questions from internal docs.
- Goals: reduce support tickets, maintain low latency, high satisfaction.

Quick start (development)
1. Copy `.env.example` to `.env` and fill provider keys.
2. docker-compose up --build
3. Backend: http://localhost:8000/docs
4. Frontend: http://localhost:3000

Components
- backend/: FastAPI + ingestion + FAISS index management
- frontend/: React + TypeScript chat UI
- infra/: k8s manifests and helm charts
- docs/: architecture & runbook
