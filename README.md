\# FraudPulse



Production-style real-time fraud detection and feature engineering platform.



\## Overview



FraudPulse is an end-to-end fraud detection platform designed to demonstrate

real-world data engineering, machine learning, analytics, and model-serving

workflows.



The platform combines a public credit-card fraud dataset for model development

with realistically generated transaction events for streaming simulation.



\## Planned Architecture



Public Fraud Data

&#x20;       ↓

Data Analysis \& Feature Engineering

&#x20;       ↓

XGBoost Model

&#x20;       ↓

MLflow

&#x20;       ↓

Synthetic Transaction Events

&#x20;       ↓

Kafka

&#x20;       ↓

Feature Engineering

&#x20;       ↓

Feast + Redis

&#x20;       ↓

Fraud Prediction API

&#x20;       ↓

Risk Decision



\## Technology Stack



\- Python

\- Pandas / NumPy

\- DuckDB

\- XGBoost

\- Scikit-learn

\- MLflow

\- Apache Kafka

\- Feast

\- Redis

\- FastAPI

\- Evidently

\- Docker

\- Pytest



\## Project Status



🚧 In development

