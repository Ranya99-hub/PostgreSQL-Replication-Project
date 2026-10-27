# PostgreSQL Replication & Performance Analysis (Week 2)

## 📊 Results Summary:
* **Async Mode:** TPS = 450.60 | RPO > 0 (Potential Data Loss)
* **Sync Mode:** TPS = 261.88 | RPO = 0 (Zero Data Loss)

## 🛠️ Troubleshooting:
Resolved port collision issues on Google Colab by isolating the Standby server on port 5433 and updating configurations dynamically.
