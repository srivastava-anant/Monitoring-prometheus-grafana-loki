
# Monitoring & Observability Stack on AWS 📈

**Prometheus · Grafana · Loki · Slack**

## Overview 🧭

This repository documents an end-to-end monitoring and observability implementationfor a web application deployed on **AWS EC2**.

The project focuses on building practical visibility into system behavior using metrics, logs, dashboards, and alerting—mirroring how observability is implemented in real production environments by DevOps and SRE teams.

---

## System Architecture 🏗️

![unnamed](https://github.com/user-attachments/assets/e51f9509-5510-451c-a5ad-28399c3fec7b)




## Technology Stack 🧰

* **AWS EC2** – Compute infrastructure
* **Prometheus** – Metrics collection and alerting
* **Grafana** – Visualization and dashboards
* **Loki** – Centralized log aggregation
* **PromQL** – Query language for metrics
* **Slack** – Alert notifications and incident awareness
* **Linux / Bash** – System configuration and automation

---

## Scope of Implementation 🔧

* Provisioned and configured a web server on AWS EC2
* Set up Prometheus to scrape system and service-level metrics
* Designed Grafana dashboards using custom PromQL queries
* Centralized application and system logs using Loki
* Implemented alert rules for key system health indicators
* Integrated Slack for real-time alert notifications
* Validated the setup through load generation and failure simulation

---

## Key Outcomes 📌

* Clear visibility into system performance and resource usage
* Ability to correlate metric anomalies with application logs
* Actionable alerting instead of alert noise
* Improved understanding of incident detection and response workflows
* Hands-on exposure to observability practices used in production systems

---

## Deployment Overview 🚀

1. Launch an AWS EC2 instance (Linux-based)
2. Install and configure Prometheus, Grafana, and Loki
3. Configure exporters and data sources
4. Create dashboards and alerting rules
5. Connect alert notifications to Slack
6. Verify metrics, logs, dashboards, and alerts


---


---

