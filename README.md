# container-monitoring-setup
Containerized Prometheus monitoring setup via Docker Compose.

# Prometheus Monitoring Stack with Docker

A professional monitoring setup using **Prometheus** and **Docker Compose** to monitor system metrics and containerized services. This project demonstrates how to orchestrate a monitoring stack in a containerized environment.

## 🚀 Overview

This repository contains a complete setup for a lightweight monitoring system. It uses Docker to deploy Prometheus and configures it to scrape metrics from various targets.

### 🛠️ Tech Stack
* **Containerization:** Docker, Docker Compose
* **Monitoring Tool:** Prometheus
* **Configuration:** YAML (Prometheus Configuration)
* **Environment:** Linux / DevOps Infrastructure

## 📂 Project Structure
```text
project-1/
├── docker-compose.yml          # Orchestrates the monitoring services
├── prometheus/
│   └── prometheus.yml          # Prometheus configuration file
└── README.md                   # Project documentation


⚙️ How It Works
Docker Compose: Orchestrates the lifecycle of the Prometheus container, ensuring networking and volume persistence are correctly configured.
Prometheus Configuration: The prometheus.yml file defines the scrape jobs, instructing Prometheus on where to fetch metrics (e.g., localhost or specific container names).
Networking: Containers communicate within a shared Docker network, allowing Prometheus to discover targets via service names.
🛠️ Getting Started
Prerequisites
Docker installed
Docker Compose installed
Installation & Running
Clone the repository:
bash
   git clone https://github.com/matiinmoradi/container-monitoring-setup.git
   cd project-1
   
Launch the stack:
bash
   docker-compose up -d
   
Access Prometheus UI:Open your browse…nd…
