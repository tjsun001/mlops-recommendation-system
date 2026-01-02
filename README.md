# MLOps Recommendation System

This repository provides a high-level overview of an end-to-end, production-style
recommendation system focused on reliability, graceful degradation, and operational
ML concerns.

The system is intentionally split into independently deployable services to
demonstrate clear ownership boundaries and failure isolation.

## System Architecture

![System Architecture](docs/architecture-diagram.png)

## Repositories

- **Backend API (Spring Boot)**  
  API contracts, ML integration, and deterministic fallback logic  
  👉 https://github.com/your-username/mlops-recommendation-backend

- **Inference Service (FastAPI)**  
  ML model loading and prediction serving  
  👉 https://github.com/your-username/mlops-recommendation-inference

- **Frontend (Next.js)**  
  UI and API proxy layer  
  👉 https://github.com/your-username/mlops-recommendation-frontend
