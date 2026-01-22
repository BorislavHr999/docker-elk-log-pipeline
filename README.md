# 🦌 Docker ELK Log Pipeline

This project demonstrates a complete **Logging Pipeline** using the Elastic Stack.

🔹 **Goal:** Ingest, process, and visualize real-time logs from a containerized application. 📉
🔹 **Stack:**
  - **Elasticsearch:** The search and analytics engine. 🗄️
  - **Logstash:** Server-side data processing pipeline (TCP Input -> ES Output). 🛠️
  - **Kibana:** Visualizing data with dashboards. 📊
  - **Alpine:** A lightweight generator sending logs via `netcat`. 🌲

---
**How to run:**
```bash
docker-compose up -d
Open http://localhost:5601 to explore the logs in Kibana! 🚀
