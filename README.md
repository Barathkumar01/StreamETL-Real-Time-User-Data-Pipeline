# 🚀 StreamETL: Real-Time User Data Pipeline

A fully containerized, production-style **real-time ETL pipeline** that streams, transforms, and stores user event data using modern big data tools. This project emulates how companies process high-velocity data in real-world applications.

---

## 📌 Project Highlights

- 🔄 Ingests user data in real-time from the `randomuser.me` API
- ⚙️ Streams data using **Apache Kafka**
- 🔍 Processes events with **Apache Spark Structured Streaming**
- 📅 Schedules and orchestrates ETL jobs using **Apache Airflow**
- 🧱 Stores transformed data in **Apache Cassandra**
- 📦 Entire stack runs via **Docker Compose**

---

## 🛠️ Tech Stack

| Component      | Purpose                              |
|----------------|--------------------------------------|
| Python         | API client and Airflow DAGs          |
| Apache Kafka   | Real-time data ingestion             |
| Apache Spark   | Stream processing and transformation |
| Apache Airflow | Workflow orchestration               |
| Cassandra      | Scalable NoSQL data storage          |
| Docker Compose | Local containerized deployment       |
| Zookeeper      | Kafka coordination                   |

---

## 📈 Realistic Metrics

- Streams ~**1,000 user events/hour**
- Simulated using public API: [randomuser.me](https://randomuser.me)
- Entire pipeline spins up in **under 2 minutes** using Docker

---

## 📊 System Architecture

![image](https://github.com/user-attachments/assets/89771f86-44a0-4ff2-a905-4e8df36d7f08)
