
# Loki 🪵

## Overview

This directory contains the configuration for **Loki**, used to centralize and query **application and system logs** as part of the observability stack.

Loki complements Prometheus by providing log visibility that can be correlated with metrics in Grafana.

---

## Purpose

* Collect and store logs from monitored services
* Enable efficient log querying and filtering
* Support incident investigation and root cause analysis

---

## Log Flow

```
Application / System Logs → Loki → Grafana
```

Logs are visualized and queried in Grafana using LogQL.

---

## Configuration

* Log ingestion is configured via Loki configuration files
* Indexing is label-based for efficient querying
* Designed to work alongside Prometheus metrics

---
