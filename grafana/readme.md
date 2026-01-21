
<img width="1918" height="949" alt="image" src="https://github.com/user-attachments/assets/06c928b6-cbc9-4808-be5f-873b1471d3ca" />


### 1. Endpoint Requests (Now & Older)

```promql
sum by (endpoint) (rate(http_requests_total[5m]))
```

Shows per-second request rate grouped by application endpoint.

---

### 2. HTTP Request Rate

```promql
sum by (endpoint) (rate(http_requests_total[1m]))
```

Displays short-term traffic rate per endpoint to catch sudden spikes.

---

### 3. Root Filesystem Usage (%)

```promql
100 - (node_filesystem_avail_bytes{mountpoint="/", fstype!="tmpfs"} / node_filesystem_size_bytes{mountpoint="/", fstype!="tmpfs"} * 100)
```

Calculates percentage of disk space used on the root filesystem.

---

### 4. Available Memory (MB)

```promql
node_memory_MemAvailable_bytes / 1024 / 1024
```

Shows currently available system memory in megabytes.

---

### 5. CPU Utilization (%)

```promql
100 - (avg by (instance) (rate(node_cpu_seconds_total{mode="idle"}[5m])) * 100)
```

Represents overall CPU usage derived from idle CPU time.

---


