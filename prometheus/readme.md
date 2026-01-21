<img width="1917" height="1018" alt="image" src="https://github.com/user-attachments/assets/50268969-4995-450d-9724-21b9fc947c22" />

# Prometheus 📊

## Overview

This directory contains the **Prometheus configuration** used for monitoring system and application metrics in the AWS-based observability stack.

Prometheus is responsible for scraping metrics, evaluating alert rules, and forwarding alerts to Alertmanager for notification delivery.

---

## Contents

* `prometheus.yml` – Defines scrape targets, scrape intervals, and Alertmanager configuration
* `alert-rules.yml` – Contains alerting rules for system health and service availability

---

## Key Responsibilities

* Collect system metrics via exporters
* Monitor service availability
* Evaluate alert conditions
* Trigger alerts for downstream notification (Slack)

