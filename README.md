# Kubernetes Monitoring & Alerting Stack

This project demonstrates a complete monitoring and alerting setup using **Prometheus, Alertmanager, Black Box Exporter, and Node Exporter** to track system and application performance.

The goal is to provide **real-time visibility**, **proactive alerting**, and **operational insights** for infrastructure running on virtual machines or Kubernetes.

<img width="1536" height="1024" alt="monitoring arc" src="https://github.com/user-attachments/assets/bfa0b1f6-782e-45f4-bded-861e0b4cc3da" />


## Overview

- Collect system and application metrics
- Store and query time-series data
- Visualize performance through dashboards
- Trigger alerts based on defined thresholds
- Send notifications via email

---

## Tech Stack

- **Prometheus** – Metrics collection & storage  
- **Alertmanager** – Alert routing & notifications  
- **Grafana** – Dashboards & visualization  
- **Node Exporter** – System metrics collection  
- **Nginx (Optional)** – Monitored service  
- **Email (Gmail SMTP)** – Alert notifications  
---

## Architecture & Workflow
```
Node Exporter  →  Prometheus  →  Alertmanager  →  Email (Gmail SMTP)
                      ↓
                   Grafana
```

## Workflow

1. Node Exporter collects system metrics (CPU, Memory, Disk)
2. Prometheus scrapes and stores metrics
3. Alert rules evaluate conditions
4. Alertmanager processes alerts
5. Notifications are sent via email
6. Grafana visualizes metrics in dashboards

---

## Features

- Real-time infrastructure monitoring  
- Custom alert rules (CPU, Memory, Disk)  
- Email alert notifications  
- Grafana dashboards for visualization  
- Scalable monitoring architecture  

---

## Screenshots

### Alert Email Example

![IMG_1484](https://github.com/user-attachments/assets/ff14ea57-827b-48bd-b18a-1a983deb38be)


---

##  Sample Alerts

- High CPU Usage  
- High Memory Usage  
- Disk Space Running Low  
- Instance Down  

---

