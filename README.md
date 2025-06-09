# Big-Data-Technologies-Project-BTC-Trades-Data-Pipeline
Project Overview
This project implements a real-time data pipeline for processing and analyzing BTC/USDT trade data from Binance's WebSocket API. The system ingests high-frequency trading data, processes it using a distributed architecture, and provides real-time analytics and price predictions through machine learning models.

## Key Features
Real-time Data Ingestion: Streams live BTC/USDT trade data from Binance WebSocket API

Distributed Processing: Uses Apache Spark for scalable data processing

Message Broker: Apache Kafka for reliable data streaming

## Storage Solutions:

InfluxDB for time-series data storage

Hadoop HDFS for historical data storage

Batch Processing: MapReduce for historical data aggregation

Machine Learning: Price prediction models (Linear Regression, Random Forest, GBT)

Visualization: Grafana dashboards for real-time monitoring


## 🛠️ Core Technologies
| Component | Educational Purpose |
|-----------|---------------------|
| Kafka | Distributed event streaming |
| Spark | Stream processing & ML |
| Hadoop | Distributed storage |
| InfluxDB | Time-series storage |
| Grafana | Visualization |


## 🧠 Key Learnings
This project illustrates:
1. Designing fault-tolerant data pipelines
2. Trade-offs between batch vs stream processing
3. Challenges in financial time-series prediction
4. Containerized big data architectures

## 📢 Important Notice
This repository and its contents are provided for educational and reading purposes only.

All materials are demonstrative and contain no production-ready code

No actual trading systems or financial advice are represented

Data sources are mentioned for academic illustration only

Not intended for real-world use - For learning big data concepts only

By accessing this repository, you acknowledge this is purely an educational resource.
