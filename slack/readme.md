<img width="1910" height="950" alt="image" src="https://github.com/user-attachments/assets/b7221452-d135-469e-b5de-4964b69b2a21" />


# Slack Alerting 🔔

## Overview

This directory contains the configuration used to deliver **Prometheus alerts to Slack** via **Alertmanager**.

Slack is used as the notification channel to ensure real-time visibility into system health, failures, and threshold breaches.

---

## Purpose

* Receive critical and warning alerts in real time
* Enable faster incident awareness and response
* Integrate monitoring alerts into team communication workflows

---

## Alert Flow

```
Prometheus → Alertmanager → Slack
```

Prometheus evaluates alert rules, Alertmanager handles routing and formatting, and Slack delivers notifications to the configured channel.

---

## Configuration

* Alerts are grouped and routed based on severity
* Slack webhooks are used for message delivery
* Sensitive values (webhooks, tokens) are not committed and are replaced with placeholders




