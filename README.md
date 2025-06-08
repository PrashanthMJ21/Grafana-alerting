# 🚨 Grafana Alerting with Prometheus

This repository contains the source code and configuration files for setting up a robust alerting and monitoring stack using **Grafana**, **Prometheus**, **Alertmanager**, and **Node Exporter**. It supports multiple server instances and visualizations for CPU, Memory, and Disk metrics, along with alerting rules configured via Grafana's unified alerting system.

---

## 📘 Report

A detailed project report covering the architecture, setup, configurations, alerting logic, and visualization strategies is available here:

📄 [Grafana Alerting Report](https://docs.google.com/document/d/1MtipcynhJ_7bQdCnv558q0_oD8T1ga0BTpK8tKettcs/edit?usp=sharing)

---

## 💡 Features

- 🔧 Multi-instance scraping via Prometheus
- 📊 CPU, Memory, and Disk usage visualized in Grafana
- 🚨 Custom alert rules per server (via job labels)
- 🔁 Persistent alert rules and dashboards
- 🔐 Optional reverse proxy setup with basic authentication (Caddy)
- 📎 GitHub/GitLab/Google OAuth authentication options for Grafana

---

## 📂 Source Code

All source code (Docker Compose, Prometheus scrape configs, Grafana provisioning, alert rules) is included in this repository.

📁 This repository hosts the complete infrastructure code required to deploy the stack.

---

## ▶️ Getting Started

```bash
git clone https://github.com/PrashanthMJ21/Grafana-alerting.git
cd Grafana-alerting
docker-compose up -d
