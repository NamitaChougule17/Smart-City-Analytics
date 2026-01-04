# 🏙️ **Real-Time Data Pipeline for Smart City Analytics**
### **Kafka • Spark • AWS • Cloud-Native Analytics**

This project implements a **real-time data streaming pipeline** to process high-velocity IoT sensor data for smart city analytics. The system ingests events using Kafka, processes data in near real-time with Apache Spark, and stores curated outputs in AWS services for analytics and visualization.

---

## 📌 **Project Overview**

The goal of this project is to design and implement a scalable, event-driven architecture for smart city use cases such as traffic monitoring, environmental sensing, and operational analytics.

The pipeline enables:
- Real-time ingestion of IoT data
- Stream processing and transformation
- Cloud-based storage and analytics
- Near real-time dashboards and insights

---

## 🧠 **Key Features**

- Event-driven ingestion using **Apache Kafka**
- Real-time stream processing with **Apache Spark**
- Cloud storage using **AWS S3**
- Analytical querying via **AWS Redshift / Athena**
- Modular, containerized deployment using **Docker Compose**
- Configurable job orchestration for streaming workloads

---

## 🏗️ **Architecture**

IoT Sensors
↓
Kafka Topics
↓
Spark Streaming Jobs
↓
AWS S3 (Curated Data)
↓
Redshift / Athena
↓
Dashboards & Analytics

---

## 🛠 **Tech Stack**

- **Apache Kafka**
- **Apache Spark**
- **Python**
- **Docker & Docker Compose**
- **AWS S3**
- **AWS Glue / Athena**
- **AWS Redshift**
- **Power BI**

---

## ▶️ **How to Run**

1. Install dependencies**
pip install -r requirements.txt
2. Start services
docker-compose up
3. Run Spark streaming job
python jobs/main.py
